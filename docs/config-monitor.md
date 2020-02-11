---
layout: default
title: Config Monitor
nav_order: 14
---

### Config Monitor
Iedis 2 provides some simple ways to config and monitor Redis server.
These operations are only available on a single server, you can use these operations by right-clicking on
your desired server:

![menu](/assets/images/config-monitor/menu2.png){:class="screenshot"}

### Config Server
All available server options are listed. Each time you select an item it's corresponding documentation will be visible
at the bottom of the list:

![server options](/assets/images/config-monitor/server-options2.png){:class="screenshot"}

The value will become editable when clicking on the value field that you want to edit. The value will be saved automatically each
time you press ```↩``` after you finish editing or change a dropdown value:

![edit server option](/assets/images/config-monitor/edit-server-option2.png){:class="screenshot"}

Use speed search to locate config options quickly:

![speed search](/assets/images/config-monitor/speed-search2.png){:class="screenshot"}

### Slow Log
Slow log lists commands which are slow, the time when it was logged and it's execution time in both ms and µs. 
Iedis 2 update them every second, you can change the size of slow log:

![slow log](/assets/images/config-monitor/slow-log2.png){:class="screenshot"}

### Client List
Iedis 2 use ```client list``` command to print information of clients currently connecting to a Redis server.
The information is updated every second.

![client list](/assets/images/config-monitor/client-list2.png){:class="screenshot"}

You can kill clients by selecting clients you want to kill and use *right-clicking -> Kill Selected Clients*:

![kill clients](/assets/images/config-monitor/kill-clients2.png){:class="screenshot"}