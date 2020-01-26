---
layout: default
title: Value Operations
nav_order: 11
---

### Values
All Redis data type (string, hash, list, set, zset) can have values.
You can view and edit them in value editor when you select a corresponding key (string) or member (hash, list, set, zset).

### Value Editor
Iedis 2 support many built-in data formats (e.g., JSON, XML, Msgpack, Pickle, etc.) which make it interact with Redis server handily.
The value of a key or a member will be formatted properly before being rendered in the value editor when you select some kind of data format.

![value editor](/assets/images/value-operations/value-editor2.png)

### Save
You can save the value by press ![save](/assets/images/value-operations/save2.png){:class="icon"} or use shortcut ```⌘ + S``` on Mac and ```Ctrl + S``` on Windows
as soon as you finish your editing in the value editor.

Value editor will ensure that value does not contain any error before being saved to Redis.
JSON and XML string will be compressed to reduce memory consuming before being saved to Redis when you invoke save action.
Some data format (e.g., Msgpack) will be represented as JSON string in the value editor for representation purpose, you can still edit the JSON and it'll be serialized using the data format you selected before being saved to Redis.

![format validate](/assets/images/value-operations/format-validate2.png)