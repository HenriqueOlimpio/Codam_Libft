# Codam_Libft
This project is about coding my own library 
## 🛠️ Usage

### Requirements

The library is written in C language and needs the **`gcc` compiler** and some standard **C libraries** to run.

### Instructions

**1. Compiling the library**

To compile the library, run:

```shell
$ cd path/to/libft && make
```

**2. Using it in your code**

To use the library functions in your code, simply include its header:

```C
#include "libft.h"
```

and, when compiling your code, add the required flags:

```shell
-lft -L path/to/libft.a -I path/to/libft.h
```

## 📋 Testing

**1. First, configure the path to the libft folder in the Makefile (inside `/testing/`):**

```Makefile
#############################
## Path to Libft directory ##
#############################
DIR		= ../
```

**2. Then run:**

```shell
make t
```
