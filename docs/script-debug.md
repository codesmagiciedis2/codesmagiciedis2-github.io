---
layout: default
title: Script Debug
nav_order: 21
---

### Debug Script
You can use all debug stuff that a debugger should provide, for instance, we can use breakpoints.
You can configure debugger via [Script Execution](script-exec).

### Debug Console
Iedis 2 launches a debug console during a debug session, you can execute Redis commands via debug console:

![debug console](/assets/images/script-debug/debug-console2.png)

### Auto Completion
Iedis 2 provide command auto-completion in debug console which is the same as [Command Execution](command-exec):

![auto completion](/assets/images/script-debug/auto-completion2.png)

### Documentation
Iedis 2 provide command documentation in debug console which is the same as [Command Execution](command-exec):

![documentation](/assets/images/script-debug/documentation2.png)

### Command Execution
Iedis 2 will print the detail of command interaction in the debugger if you choose Print Redis call detail when stepping over in [Script Execution](script-exec).
This is pretty useful to determine that how your script affects the data set:

![command execution detail](/assets/images/script-debug/command-execution-detail2.png)

You can use ```redis.debug()``` to print debug message to serve as logger.debug() for debugging purpose:

![debug message](/assets/images/script-debug/debug-message2.png)

**Note**: This is available when you use breakpoints.

### Code Evaluation
You can run other Lua script while you're debugging an existing script. You can evaluate code by *right-click on Lua editor -> select Evaluate Expression*: 

![evaluate expression](/assets/images/script-debug/evaluate-expression2.png)

You can execute script via evaluate expression dialog:

![evaluate expression dialog](/assets/images/script-debug/evaluate-expression-dialog2.png)

If your script is long you can switch to evaluate code fragment mode: 

![evaluate code fragment](/assets/images/script-debug/evaluate-code-fragment2.png)

A string with a single world will be determined as a variable, 
and Iedis 2 will use ```PRINT``` command to display it's current value in current debug session. 
Otherwise, Lua script will be evaluated using ```EVAL``` command.

**Note**: The ```EVAL``` command is executed in a different call frame.

### Watcher
You can use watcher to monitor things to help you debugging easier:

![watcher](/assets/images/script-debug/watcher2.png)