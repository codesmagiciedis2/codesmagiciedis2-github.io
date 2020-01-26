---
layout: default
title: Key Explorer
nav_order: 7
---

### Key Explorer
```Key Explorer``` is the place where you can interact with Redis server handily. 
You can do many things here, add new keys, finding keys using patterns, edit values, etc.

Select your desired Redis server and click ![search](/assets/images/key-explorer/search2.png){:class="icon"} or double clicking on server label to open key explorer editor.
You can use any node (master or slave) if Redis is running under cluster mode, Iedis 2 takes care of everything else.

![open key explorer](/assets/images/key-explorer/open-key-explorer2.png)

Key explorer was built with many useful areas which make it much easier to interact with Redis server:

![key explorer](/assets/images/key-explorer/key-explorer2.png)

**Note**: We don't need to open different key explorers for different nodes in the cluster as Iedis 2 will scan the cluster to match the pattern

### Popup Menu
Key operations are also available as popup menu for convenience, you can right-click on matching keys area to make them visible: 

![key operations](/assets/images/key-explorer/key-operations2.png)