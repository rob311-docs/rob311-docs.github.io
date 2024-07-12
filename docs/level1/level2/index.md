---
layout: default
title: level 2
nav_order: 2
has_children: true
parent: level 1
---
 
This is level 2's index file, in the .md file, we have the settings:

```
layout: default
title: level 2
nav_order: 2
has_children: true
parent: level 1
```

- `nav_order` is where this page at on the navigation bar on the left hand side. It is 2nd, because 1st is the "latex is supported" page.
- `has_children: true` means level 2 has children as well.
- `parent: level 1`: parent needs to be defined, otherwise this child won't show up on the nav bar.