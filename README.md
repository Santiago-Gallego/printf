# 0x11. C - printf

## Overview
The goal of this project is to create a custom `printf` function


## Requirements

* Allowed editors: `vi`, `vim`, `emacs`
* All your files will be compiled on Ubuntu 14.04 LTS
* Your programs and functions will be compiled with gcc 4.8.4 using the flags `-Wall -Werror -Wextra and -pedantic`
* All your files should end with a new line
* Your code should use the `Betty` style. It will be checked using `betty-style.pl` and `betty-doc.pl`
* You are not allowed to use global variables
* No more than 5 functions per file
* In the following examples, the **[main.c](main.c)** files are shown as examples. You can use them to test your functions, but y\
ou don’t have to push them to your repo (if you do we won’t take them into account). We will use our own **[main.c](main.c)** fil\
es at compilation. Our **[main.c](main.c)** files might be different from the one shown in the examples
* The prototypes of all your functions should be included in your header file called **[holberton.h](holberton.h)**
* Don’t forget to push your header file
* All your header files should be include guarded


## Authorized functions and macros

* `write`
* `malloc`
* `free`
* `va_start`
* `va_end`
* `va_copy`
* `va_arg`


## Tasks

Format specifier | Operation
---------------- | ---------
%c | Prints the value of a type char argument
%i | Prints the value of an type integer argument
%d | Prints the value of an type integer floating argument
%s | Prints the value of an *char argument
%% | Prints only the modulo
%b | Converts an integer argument to binary


## Files

Filename | Description
-------- | ----------
**[README.md](README.md)** | General description of the repository
**[printf.c](printf.c)** | Most important function
**[holberton.h](holberton.h)** | Header file
**[man_3_printf](man_3_printf)** | Man page for the _printf function
**[op_funcs.c](op_funcs.c)** | First Functions that writes Specific Formats
**[op_funcs2.c](op_funcs2.c)** | Second Functions that writes Specific Formats
**[buffer_int.c](buffer_int.c)** | Buffer Functions
**[buffer_ops.c](buffer_ops.c)** | First Buffer Options
**[buffer_ops2.c](buffer_ops2.c)** | Second Buffer Options
**[opid.c](opid.c)** | Main Structures
**[main.c](main.c)** | Test file

### Author

Santiago Gallego ([Santiago-Gallego](https://github.com/Santiago-Gallego)), Juan David Suarez ([juandsuarezz](https://github.com/juandsuarezz)) at [Holberton School](https://www.holbertonschool.com/)

Mar - 2020