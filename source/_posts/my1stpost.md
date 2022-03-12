---
title: my1stpost
date: 2022-03-12 00:52:59
tags:
---
**WoW, it worked**

### gcc -l links with a library file.  
For static library file libmath.a use -lmath:  
```bash
$ gcc -static myfile.c -lmath -o myfile
```
For shared library file libmath.so use -lmath:
```bash
$ gcc myfile.c -lmath -o myfile
$ gcc -lmath -lpthread thread1.c
