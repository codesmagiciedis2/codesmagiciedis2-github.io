---
layout: default
title: Find Keys
nav_order: 13
---

### Find Keys
You can use pattern matching to find keys easily and quickly.
Just type your pattern you want to use in pattern editor and click ![execute](/assets/images/find-keys/execute.png){:class="icon"} or use shortcut ```⌘ + ↩``` on Mac and
```Ctrl + ↩``` on Windows to execute scan operation:  

![pattern match](/assets/images/find-keys/pattern-match2.png){:class="screenshot"}

You can use as many patterns as you like, just make sure that they're separated by new line: 

![multi patterns](/assets/images/find-keys/multi-patterns2.png){:class="screenshot"}

Use speed search to locate keys quickly:

![speed search](/assets/images/find-keys/speed-search2.png){:class="screenshot"}

**Note**: Iedis 2 will take care of everything if Redis server is running under cluster mode.

### Pagination
Iedis 2 won't return all keys at once that matched by a pattern because it's based on Redis ```scan``` command.
You can scan more keys by clicking ![forward](/assets/images/find-keys/forward2.png){:class="icon"} or use shortcut ```⌥ + ⬇``` on Mac and ```Alt + ⬇``` on Windows:

![pagination](/assets/images/find-keys/pagination2.png){:class="screenshot"}

**Note**: Iedis 2 will take care of everything if Redis server is running under cluster mode.

### Pattern History
Iedis 2 will remember all patterns you type in pattern editor. You can browse them quickly in history dialog by click ![history](/assets/images/find-keys/history2.png){:class="icon"} or use shortcut
```⌥ + ⌘ + E``` on Mac and ```Alt + Ctrl + E``` on Windows.

![pattern history](/assets/images/find-keys/pattern-history2.png){:class="screenshot"}

You can select a pattern by using shortcut ```↩``` and it will get executed immediately.

### Pattern Auto-completion
Iedis 2 provide pattern auto-completion based on pattern history while you're typing in the pattern editor.
This is a very useful feature no matter you want to reuse a history pattern or use a new pattern by modifying a existing one. 

![pattern completion](/assets/images/find-keys/pattern-completion2.png){:class="screenshot"}