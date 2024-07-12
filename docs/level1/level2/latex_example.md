---
layout: default
title: latex example
nav_order: 1
parent: level 2
grand_parent: level 1
---

This is latex example, also, since this is the lowest level of the tree, this setting not only has parent, but also has grand_parent:
```
layout: default
title: latex example
nav_order: 1
parent: level 2
grand_parent: level 1
```

$$
\begin{equation}
\int_0^x \sin(x) dx
\end{equation}
$$

The _characteristic polynomial_ $$\chi(\lambda)$$ of the
$$3 \times 3$$ matrix  
    $$
\left( \begin{array}{ccc}
a & b & c \\
d & e & f \\
g & h & i \end{array} \right)
$$  
is given by the formula  
    $$
\chi(\lambda) = \left| \begin{array}{ccc}
\lambda - a & -b & -c \\
-d & \lambda - e & -f \\
-g & -h & \lambda - i \end{array} \right|.
$$

More examples [here](https://just-the-docs.github.io/just-the-docs-tests/components/math/katex/tests/).