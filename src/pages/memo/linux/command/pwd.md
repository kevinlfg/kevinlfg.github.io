---
layout: ../../../layouts/MemoLayout.astro
title: 'Example command'
description: 'Example'
tags: ["linux","command"]
---

## Purpose

pwd = Print Working Directory

## Example

```console
user@host:~$ pwd
/home/user
```

```console
user@host:~$ cd ./app
user@host:~$ mkdir service
user@host:~$ ln -s service servicelink
user@host:~$ cd servicelink

user@host:~$ pwd -P
/home/user/app/service

user@host:~$ pwd -L
/home/user/app/servicelink
```

## Argument/Flag/Options

| Option | Description |
| :-: | :- |
| `-L` | Print logical path |
| `-P` | Print physical path |
