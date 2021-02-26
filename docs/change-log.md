---
layout: default
title: Change Log
nav_order: 100
---
### 2021.1
  * New Features
      * Support decoding PHP session (php format)

### 2020.1.1
  * Fixes
       * Can't connect to server

### 2020.1
  * New Features
      * Clone member
      * Support Unix Domain Sockets
      * Ensure member name doesn't exist when add/clone member
      * Report bug just from IDE
  * Updates
      * Use default value when add new member for lit/set/zset
      * Use smaller minimum size for the left most panel

### 2019.3
  * New Features
      * Support SSL/TLS
      * Redis key auto-completion
      * Clone server configuration
  * Updates
      * Trim host name when connecting to Redis server
      * Show concrete error message if Iedis 2 can't connect to Redis server
      * Use password storage to store sensitive data
      * Show existing DB only in tree viewer

### 2019.2.3
  * New Features
      *  We can now use selected patterns (Instead of whole patterns) to scan keys in KeyExplorer
      *  Directly press enter to edit member elements
      *  Make sure 'Flush DB' action won't be applied by mistake
      *  Use default selection color in various themes
      *  Open same KeyExplorer and TreeViewer editor for different cluster nodes
      *  Simplify member elements
      *  Simplify key summary
      *  Try to use last selected value editor after failing to decode value
  * Fixes
       * 'soft wrapping' issue
       * 'Keyboard arrows don't work in member views' issue

### 2019.2
  * New Features
      * Use new license model
      * View databases and key/value in a tree manner
      * Focus proper component after executing actions
      * Upgrade Jedis to 3.0.1
      * Update connection timeout to a larger value
      * Update icons
      * Add 'FlushDB' action
      * Suggest new key name when clone/add new key
      * Directly press enter to rename key when it's selected
      * Use balloon notification instead of warning dialog when value can't be decoded
      * Use shorter file name for Redis editor
      * We can now set TTL for multiple keys
      * We can now delete multiple keys
      * We can now delete multi members at the same time
      * Stop background task when Iedis window loses focus
      * Resource usage optimization
      * Sort members in tree viewer and key explorer
      * Persist editor state when it's closed
  * Fixes
      * 'Infinite error message if value can't be decoded' issue
