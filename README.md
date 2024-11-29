# MY 42 Libft
## Description

Libft is the first library I developed during my time at 42 School. This project required recreating essential functions from the C standard library (libc) and implementing additional utility functions that are not part of the standard library but are commonly needed in programming.

The goal of this project was to understand how standard library functions work internally and to build a reusable library that I can use in future projects. By implementing these functions from scratch, I gained a deeper understanding of memory management, string manipulation, and working with linked data structures in C.

The library includes two main parts:

  - Standard C Library Functions: These are recreations of functions like strlen, memcpy, atoi, and more. They mimic the behavior of their standard counterparts but are prefixed with ft_ to avoid naming conflicts.
  - Additional Utility Functions: These include functions like ft_substr, ft_strjoin, ft_split, and ft_itoa, which are designed to simplify common programming tasks such as string manipulation, memory allocation, and dynamic data management.

An optional bonus section extends the library with functions for handling linked lists. Using the t_list structure, these functions provide a robust way to create, manipulate, and free linked lists.

Libft is not just a coding exercise but also a valuable tool that I continue to expand and refine. I have used it as a foundation for many other projects throughout my C programming journey at 42 School. It has become an essential part of my workflow, helping me write cleaner and more efficient code.
## Installation

Clone the repository:
```
git clone https://github.com/your-account/libft.git
```
Compile the library:
```
make
```
This will generate the libft.a static library, which can be linked to other C projects.
## Usage

Include libft.a in your project by linking it during compilation:
```
gcc -Wall -Wextra -Werror -L. -lft your_program.c -o your_program
```
Include the libft.h header in your source files:
```
#include "libft.h"
```
Use the library's functions as you would standard C library functions, with the added ft_ prefix.
