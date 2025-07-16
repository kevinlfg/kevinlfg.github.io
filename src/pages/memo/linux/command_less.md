---
layout: ../../../layouts/MemoLayout.astro
title: 'less command'
description: 'Used to inspect a text file'
tags: ["linux","command","text","file"]
---

###### In console :
``` Bash
less [OPTIONS] filename
less -N filename # Display line numbers
less -X filename # By default, when exiting the command, the text disapear. -X will keep the text displayed
less +F filename # Follow mode to monitor any changes to the file
```

###### Actions :
| Action | Key | Example | Comments |
|---|---|---|---|
| Search | `/text_to_search` | - | - |
| Next occurence of the search | `n` | - | - |
| Previous occurence of the search | `N` | - | - |
|-|-|-|-|
| Next Page | `f` or `Space bar` | - | - |
| Previous Page | `b` | - | - |
| Go x lines forward | `xf` | `50f` to go 50 lines forward | - |
| Go x lines backward | `xb` | `50f` to go 50 lines forward | - |
| Go to the top | `g` | - | - |
| Go to the bottom | `G` | - | - |
| Go to line x | `xg` | `50g` to go to the line 50 | - |
| Go to the top | `p` | - | - |
| Go to x percent of the file | `xp` | `50p` to go to the middle of the of the file | - |
| Help | `h` | - | - |
| Quit | `q` | - | - |
