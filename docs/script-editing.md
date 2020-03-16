---
layout: default
title: Script Editing
nav_order: 20
---

### Method Completion
Iedis 2 provides method name auto-completion while you're invoking ```redis.``` or using KEYS, ARGV

![method completion](/assets/images/script-editing/method-completion2.png){:class="screenshot"}

### Command Completion
Iedis 2 provides command auto-completion while you're invoking ```redis.call()```.
Command completion are aware of context for convenience:

![command completion](/assets/images/script-editing/command-completion2.png){:class="screenshot"}

### Documentation
Place your caret at any command character and use shortcut ```F1``` to show quick documentation of a command, documentation will be rendered very quickly as they are offline: 

![documentation](/assets/images/script-editing/documentation2.png){:class="screenshot"}

### Lua Stuff
All other Lua language stuff is supported by EmmyLua plugin.