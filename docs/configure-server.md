---
layout: default
title: Configure Server
nav_order: 5
---

### Add a New Server
You can click ![add](/assets/images/configure-server/add2.png){:class="icon"} or use shortcut ```⌘ + N``` on Mac and ```Alt + Insert``` on Windows to open add server dialog:

![add server button](/assets/images/configure-server/add-server-button2.png){:class="screenshot"}

You're now ready to configure your Redis server. You'll be asked to provide both your Redis server host and port to add a new server,
you need to fill in the password field if your Redis server needs authentication. 
You can also label your servers with meaningful names if you have many different Redis servers to manage:

![add server](/assets/images/configure-server/add-server2.png){:class="screenshot"}

You can switch to SSH tab to set up a proxy if you need to use a proxy to connect to your Redis server:

![ssh](/assets/images/configure-server/ssh2.png){:class="screenshot"}

Use ```Test Connection``` to test your configuration before confirming your configuration to make sure everything is well configured:
 
![test connection](/assets/images/configure-server/test-connection2.png){:class="screenshot"}


### Edit a Server
Select the server that you want to edit and click ![edit](/assets/images/configure-server/edit2.png){:class="icon"} or use shortcut ```Shift + F6``` to open edit server dialog which is almost the same as add server dialog:

![edit serve](/assets/images/configure-server/edit-server2.png){:class="screenshot"}

### Remove a Server
Select the server that you want to remove and click ![remove](/assets/images/configure-server/remove2.png){:class="icon"} or use shortcut ```Delete``` on Mac and ```Backspace``` on Windows to remove a Redis server:

![remove server](/assets/images/configure-server/remove-server2.png){:class="screenshot"}

### Refresh servers
There are some situations, for instance, server mode can't be detected automatically due to server restart, you need to refresh Redis servers. Just click ![refresh](/assets/images/configure-server/refresh2.png){:class="icon"} to refresh them all:

![refresh server](/assets/images/configure-server/refresh-server2.png){:class="screenshot"}

### Popup Menu
There operations are also available as popup menu for convenience, you can right-click on server list to make them visible:

![popup menu](/assets/images/configure-server/popup-menu2.png){:class="screenshot"}

### Cluster
You can use any node to configure Redis server if it is running under cluster mode, Iedis 2 takes care of everything for it at runtime.

Iedis 2 will list all master and slave nodes in case if you want to connect to it to use some functionality which is only available on a single server, for instance, [Advanced Console](advanced-console).

![cluster](/assets/images/configure-server/cluster2.png){:class="screenshot"}