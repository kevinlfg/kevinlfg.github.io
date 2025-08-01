---
layout: ../../../layouts/MemoLayout.astro
title: 'bc command'
description: 'Linux command bc (basic calculator)'
tags: ["linux","command"]
---

bc = basic calculator

## Interactive use

```
~> bc
bc 1.06.95
Copyright 1991-1994, 1997, 1998, 2000, 2004, 2006 Free Software Foundation, Inc.
This is free software with ABSOLUTELY NO WARRANTY.
For details type `warranty'.
1+1
2
quit
```

## Script use

```
~> licence_used=150
~> licence_total=200
~> echo "scale=2; ($licence_used / $licence_total * 100)" | bc
75
```
