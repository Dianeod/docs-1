---
title: Equal – Reference – kdb+ and q documentation
description: Equal is a q operator that flags where its arguments are equal.
author: Stephen Taylor
keywords: equal, kdb+, q
---
# `=` Equal



Syntax: `x = y`, `=[x;y]`

Returns `1b` where (items of) `x` and `y` are equal.

```q
q)(3;"a")=(2 3 4;"abc")
010b
100b
```

Equal is an atomic function.

:fontawesome-regular-hand-point-right: 
Basics: [Comparison](../basics/comparison.md)
