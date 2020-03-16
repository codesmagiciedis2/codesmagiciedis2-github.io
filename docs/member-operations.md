---
layout: default
title: Member Operations
nav_order: 11
---

### Member Operations
```hash```, ```list```, ```set```, ```zset``` have member operations, ```string``` does not have any member operation because it only has value.
Member operation will become visible when you select a corresponding key. Different key type have different member operations, let's illustrate them one by one.

**Note**: Member operations are used to manipulate members instead of their corresponding value ([Value Operations](value-operations)).

### Hash
You can add fields to hash, rename fields and remove fields from hash.

##### Add a Field
To add a new field to hash, you can click ![add](/assets/images/member-operations/add2.png){:class="icon"} or use shortcut ```⌘ + N``` on Mac and ```Alt + Insert``` on Windows to open add field dialog:

![add hash field](/assets/images/member-operations/add-hash-field2.png){:class="screenshot"}

##### Rename a Field
There are many ways to rename a field:
* Select the field and click ![edit](/assets/images/member-operations/edit2.png){:class="icon"}
* Select the field and use shortcut ```Shift + F6```
* Double click on the field
* Use popup menu by right-clicking on the field

All these three operations will make the field editable, then you can rename it and press ```↩``` when you're done:

![rename hash field](/assets/images/member-operations/rename-hash-field2.png){:class="screenshot"}

##### Remove a Field
Select the field that you want to remove and click ![remove](/assets/images/member-operations/remove2.png){:class="icon"} or use shortcut ```⌘ + Del``` on Mac or ```Alt + Del``` on Windows to remove a field.

### List
You can add values to a list and remove values from a list.

##### Add a Value
To add a new value to list, you can click ![add](/assets/images/member-operations/add2.png){:class="icon"} or use shortcut ```⌘ + N``` on Mac and ```Alt + Insert``` on Windows to open add value dialog:

![add list value](/assets/images/member-operations/add-list-value2.png){:class="screenshot"}

##### Remove a Value
Select the value that you want to remove and click ![remove](/assets/images/member-operations/remove2.png){:class="icon"} or use shortcut ```⌘ + Del``` on Mac or ```Alt + Del``` on Windows to remove a value.

### Set
You can add members to a set and remove members from a set.

##### Add a Member
To add a new member to set, you can click ![add](/assets/images/member-operations/add2.png){:class="icon"} or use shortcut ```⌘ + N``` on Mac and ```Alt + Insert``` on Windows to open add member dialog:

![add set member](/assets/images/member-operations/add-set-member2.png){:class="screenshot"}

##### Remove a Member
Select the member that you want to remove and click ![remove](/assets/images/member-operations/remove2.png){:class="icon"} or use shortcut ```⌘ + Del``` on Mac or ```Alt + Del``` on Windows to remove a member.

### ZSet
You can add members to zset, change member scores and remove members from zset.

##### Add a Field
To add a new member to zset, you can click ![add](/assets/images/member-operations/add2.png){:class="icon"} or use shortcut ```⌘ + N``` on Mac and ```Alt + Insert``` on Windows to open add member dialog:

![add zset member](/assets/images/member-operations/add-zset-member2.png){:class="screenshot"}

##### Change Member Score
There are many ways to change the score of a member:
* Select the score and click ![edit](/assets/images/member-operations/edit2.png){:class="icon"}
* Select the score and use shortcut ```Shift + F6```
* Double click on the score
* Use popup menu by right-clicking on the score

All these three operations will make the score editable, then you can rename it and press ```↩``` when you're done:

![change zset score](/assets/images/member-operations/change-zset-score2.png){:class="screenshot"}

##### Remove a Member
Select the member that you want to remove and click ![remove](/assets/images/member-operations/remove2.png){:class="icon"} or use shortcut ```⌘ + Del``` on Mac or ```Alt + Del``` on Windows to remove a member.

### Copy a Member Name
Sometimes you need to copy the name of a member or the score value of zset member, you can use shortcut ```⌘ + C``` on Mac and ```Ctrl + C``` on Windows to copy them.
You can also right-click on the member and select ```Copy``` on the popup menu to copy the name of the member. 