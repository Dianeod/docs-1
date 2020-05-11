---
title: neg – Reference – kdb+ and q documentation
description: neg is a q keyword that returns the negation of its argument. 
author: Stephen Taylor
keywords: kdb+, math, mathematics, neg, negate, negative, q
---
# `neg`



Syntax: `neg x`, `neg[x]`

Returns the negation of boolean or numeric `x`.
```q
q)neg -1 0 1 2
1 0 -1 -2
```

`neg` is an atomic function.


## Domain and range

```txt
domain b g x h i j e f c s p m d z n u v t
range  i . i h i j e f i . p m d z n u v t
```

Range: `ihjefpmdznuvt`

:fontawesome-regular-hand-point-right:
[Subtract](subtract.md)  
Basics: [Mathematics](../basics/math.md)