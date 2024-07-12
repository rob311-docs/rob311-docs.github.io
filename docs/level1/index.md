---
layout: default
title: level 1
nav_order: 2
has_children: true
---

This is level 1's index file, in the .md file, we have the settings:

```
layout: default
title: level 1
nav_order: 2
has_children: true
```

- `nav_order` is where this page at on the navigation bar on the left hand side. It is 2nd, because 1st is the Home page.
- `has_children: true` means level 1 has children, the child can be page, also can be a folder. In this template, `level 1` has 2 children, one is `latex_is_supported.md`, another one is folder `level 2`.
