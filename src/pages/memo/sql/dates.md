---
layout: ../../../layouts/MemoLayout.astro
title: 'SQL Date'
description: 'SQL condition on date'
tags: ["linux","command"]
---

# SQL Server

```
# Rows where start_date is between 2025-01-01 (included) and 2025-01-08 (excluded)
SELECT *
FROM table
WHERE start_date >= TO_DATE('2025-01-01','YYYY-MM-DD')
AND end_date < TO_DATE('2025-01-08','YYYY-MM-DD') 
ORDER BY start_date;

# All rows where start_date is more than 7 days ago
SELECT *
FROM table
WHERE start_date <= CURRENT_DATE - 7
ORDER BY start_date
```
