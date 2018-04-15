# I/O Library (C)

## Introduction

A couple of standard input/output library functions that can be useful. Mainly
used for printing and logging.

## Install

In the source file where you want to use these functions, include it using:
```
#include "../relative/path/to/io.h"
```

Then link it to your program by first compiling the source file into an object
file:
```
gcc [options] -o io.o -c io.c
```

and then linking it to your program with all the other object files you've
compiled:
```
gcc [options] -o PROGRAM obj1.o obj2.o ... io.o
```

## Uninstall

Remove the source and header files, the include statement(s) pointing to *io.h*,
and any compilation steps, if present in some Makefile.
