---
layout: default
title: Command Execution
nav_order: 18
---

### Commands
Almost all commands can be executed via Iedis 2 including blocking ones, for instance, SUBSCRIBE. 

### Execute Commands Partially
Select the commands that you want to execute and click ![execute](/assets/images/command-exec/execute.png){:class="icon"} or use shortcut ```⌘ + ↩``` on Mac and
```Ctrl + ↩``` on Windows to execute the selected commands:  

![execute partially](/assets/images/command-exec/execute-partially2.png){:class="screenshot"}

### Execute All Commands
Select nothing or select all commands, then click ![execute](/assets/images/command-exec/execute.png){:class="icon"} or use shortcut ```⌘ + ↩``` on Mac and
```Ctrl + ↩``` on Windows to execute all commands:

![execute all](/assets/images/command-exec/execute-all2.png){:class="screenshot"}

### Commands History

![command history](/assets/images/command-exec/command-history.png){:class="screenshot"}

Commands won't get executed automatically when it's copied from history dialog because Iedis 2 has no idea of what's your script doing.

### Execute Result
All commands are executed one by one. Iedis 2 stops executing subsequent commands if any command execution error happens.

The result of each command will be present with a tab in the result panel at the bottom of IDE.
We also make the result of some frequently used commands much more human readable.
 
![execute result](/assets/images/command-exec/execute-result2.png){:class="screenshot"}

### Blocking Commands
Blocking commands, for instance, SUBSCRIBE, will get a new tab to present the result each time a new message is received.

![blocking commands2](/assets/images/command-exec/blocking-commands2.gif){:class="screenshot"}

### View As
You can view command execute result as JSON, XML, etc.

![view as](/assets/images/command-exec/view-as2.png){:class="screenshot"}

### Stop Executing
We can stop command execution, for instance, to terminate a blocking command. 
To stop the execution, we can click ![terminate](/assets/images/command-exec/terminate.png){:class="icon"} or use the shortcuts ```⌘ + F2``` on Mac and ```Ctrl + F2``` on Windows:

![stop executing](/assets/images/command-exec/stop-executing2.png){:class="screenshot"}