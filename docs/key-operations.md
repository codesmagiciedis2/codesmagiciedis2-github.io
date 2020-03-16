---
layout: default
title: Key Operations
nav_order: 10
---

### Add a Key
Click ![add](/assets/images/key-operations/add2.png){:class="icon"} or use shortcut ```⌘ + N``` on Mac and ```Alt + Insert``` on Windows to open add key dialog:

![add key button](/assets/images/key-operations/add-key-button2.png){:class="screenshot"}

Specify the key name and key type you want the key to be:

![add new key](/assets/images/key-operations/add-new-key2.png){:class="screenshot"}

A value will be set as placeholder when you add a key, you can edit the value after you click the OK button:

![value placeholder](/assets/images/key-operations/value-placeholder2.png){:class="screenshot"}

### Clone a Key
You can clone a key with a different key name and the value will be copied as same as source key.
To clone a key, you need to select the key that you want to copy from and click ![copy](/assets/images/key-operations/copy2.png){:class="icon"} or use shortcut ```⇧ + ⌘ + C``` on Mac and
```Shift + Ctrl + C``` on Windows to open clone key dialog where you can specify a new key name:

![clone a key](/assets/images/key-operations/clone-a-key2.png){:class="screenshot"}

**Note**: By default, Iedis 2 use currently selected key name as a suggestion for the new key when you add/clone a key.

### Rename a Key
There are many ways to rename a key:
* Press ```Enter``` key when a key is selected
* Select the key and click ![edit](/assets/images/key-operations/edit2.png){:class="icon"}
* Select the key and use shortcut ```Shift + F6```
* Double click on the key
* Use popup menu by right-clicking on the key

All these three operations will make the key editable, then you can rename it and press ```↩``` when you're done:

![rename a key](/assets/images/key-operations/rename-a-key2.png){:class="screenshot"}

**Change key type**: You can't change the key type on the fly. You need to delete the key and add it again with a new type. 

### Remove Keys
Select the keys that you want to remove and click ![remove](/assets/images/key-operations/remove2.png){:class="icon"} or use shortcut ```⌘ + Del``` on Mac or ```Alt + Del``` on Windows to remove keys.
You can remove multi keys at once in this way:

![remove keys](/assets/images/key-operations/remove-keys2.png){:class="screenshot"}

### Copy a Key
Sometimes you need to copy the name of a key, you can use shortcut ```⌘ + C``` on Mac and ```Ctrl + C``` on Windows to copy the name of a key.
You can also right-click on a key and select ```Copy``` on the popup menu to copy the name of a key. 

### Set TTL
You can select as many keys as you like and set TTL for both of them:

![set ttl](/assets/images/key-operations/set-ttl.png){:class="screenshot"}

### Flush DB
Flush DB is also available, but you need to carefully use this action because it will remove all data in the database you selected:

![flush db](/assets/images/key-operations/flush-db.png){:class="screenshot"}