# Keter
```
undone
```
No based one-time IO language

## Why no based?
From now on, languages are leashed by implementation. x86, x64, arm, and so on.  
Is C really X-platform language? Are they really X-platform languages based on C? So I started this insane project.

## Why one-time IO?
CPU is not efficient.  
Because of von neumann sturcture.  
Because of bottleneck from store and restore.  
Because of latency of human, program have to save data in data structure.  
If procedure goes one-time-in and one-time-out, all programs are O(1).  

## How to use?
```
wrap main.k main.c
wrap main.k main.py
wrap main.k main.js
wrap main.k main.exe
wrap main.k main.out
```
