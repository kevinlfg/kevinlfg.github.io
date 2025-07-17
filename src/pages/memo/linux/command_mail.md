---
layout: ../../../layouts/MemoLayout.astro
title: 'mail command'
description: 'Linux command mail'
tags: ["linux","command"]
---

In console :

```
# Send a mail with a subject, a body and an attachment
echo "Here is the body of the mail" | mail -s "Subject" -a /appli/myapp/DATA/ARCHIVE/FILE_20250101_33.csv mymail@gmail.com
```
