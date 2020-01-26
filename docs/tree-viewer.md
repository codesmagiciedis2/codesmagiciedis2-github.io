---
layout: default
title: Tree Viewer
nav_order: 13
---

### Key Viewer
Select your desired Redis server and click ```Open Tree Viewer``` or double clicking on server label to open key explorer editor.

![tree viewer](/assets/images/tree-viewer/tree-viewer.png)

### DB Size

Iedis 2 will fetch DB size asynchronously when tree viewer is opened. DB without any keys will be shown using gray color.

![db size](/assets/images/tree-viewer/db-size.png)

### Reload

We can use ```Reload``` action to reload the keys in a database, keys matching a namespace or the value of a key.

![reload](/assets/images/tree-viewer/reload.png)

### Delete Namespace

We can delete key all keys matching a namespace using ```Delete Namespace``` action.

![delete namespace](/assets/images/tree-viewer/delete-namespace.png)

### Filter Keys

We can use a pattern to filter the keys we want.

![filter key](/assets/images/tree-viewer/filter-key.png)


### Custom Separator

By default, Iedis 2 uses ```:``` to separate keys to build the key tree, you can change it via ```Changge Separator``` action.

![custom sep](/assets/images/tree-viewer/custom-sep.png)

### Other Actions

There are many other actions which we have saw in [Key Operations](key-operations).