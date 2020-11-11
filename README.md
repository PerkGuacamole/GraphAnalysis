Graph Algorithm Performance Analysis on Persistent Memory Machines
===

This project conducts an experiment of a graph algorithm's performance on persistent memory machines.

Dependencies
---
___
Linux OS \
C++17 compliant compiler. (g++ 9.3.0 was used for this project) \
[PDMK](https://github.com/pmem/pmdk/) (libpmemobj) \
[Memkind](https://github.com/memkind/memkind)

Build
---
___
To build the program:
```console
user@dir:~$ make
```

To build in debug mode:
```console
user@dir:~$ make debug
```

Make sure to clean when switching between release and debug

To build the assembly:
```console
user@dir:~$ make assembly
```

Run
---
___
To run the program, run:
```console
user@dir:~$ ./graph_analysis
```

Clean
---
___
To delete all built files, run:
```console
user@dir:~$ make clean
```