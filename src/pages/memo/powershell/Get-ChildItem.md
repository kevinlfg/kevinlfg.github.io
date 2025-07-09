---
layout: ../../../layouts/MemoLayout.astro
title: 'Get-ChildItem command'
description: 'Powershell command : Get-ChildItem'
tags: ["windows","powershell"]
---

## Console use

```
Get-ChildItem -Path "C:\Users\kevinlfg\4*" -Recurse | Where-Object { $_.LastWriteTime -lt (Get-Date).AddDays(-2) }
```
