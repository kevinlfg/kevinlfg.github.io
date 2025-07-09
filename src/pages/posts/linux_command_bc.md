---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Linux command'
description: 'Linux command bc (basic calculator)'
tags: ["linux","command"]
---

## Interactive use

```Shell
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

```Shell
$licence_used=150
$licence_total=200
echo "scale=2; ($licence_used / $licence_total * 100)" | bc
# 75
```
