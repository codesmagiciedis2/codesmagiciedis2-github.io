---
layout: default
title: Script Execution
nav_order: 21
---

### Create Run Configuration
You need to create a run configuration before running Lua script, just right click on Lua editor and select ```Create Run Configuration```: 

![create run configuration](/assets/images/script-exec/create-run-configuration2.png){:class="screenshot"}

### Configure Run Configuration
There are some options you can configure in run configuration dialog:
* Specify on which server the script should run on
* Choose the database the script should run against
* Whether to print the detail of each Redis command execution when stepping over
* Use sync mode to debug or not
* Set key and arg values if your script needs them

![run configuration](/assets/images/script-exec/run-configuration2.png){:class="screenshot"}

You can change your run configuration later by select ```Select Run/Debug Configuration```:

![config run configuration](/assets/images/script-exec/config-run-configuration2.png){:class="screenshot"}

### Keys and Args
You can skip setting key and arg values in run configuration, Iedis 2 will ask you to provide them when you try to run the script if Iedis determines that KEYS or ARGV are required.
Defined key and arg values are cached so that you don't need to provide them each time you run the script. You can change cached values in previous run configuration.

![key arg values](/assets/images/script-exec/key-arg-values.png){:class="screenshot"}

### Run/Debug Script
You can start run/debug your script by clicking ![execute](/assets/images/script-exec/execute.png){:class="icon"} or ![debug](/assets/images/script-exec/debug.png){:class="icon"} :

![run debug](/assets/images/script-exec/run-debug2.png){:class="screenshot"}

**Coming soon**: Run script on any node of a cluster. 