# Libft

## Introduction
Libft is a project that aims to reimplement some standard C library functions, as well as some additional utility functions that can be useful for later projects. This project is a stepping stone in understanding the basics of C programming, memory management, and algorithm implementation.


## Features
A library of utility functions, including:

Memory manipulation: ft_memset, ft_bzero, ft_memcpy, ft_memccpy, ft_memmove, ft_memchr, ft_memcmp

String manipulation: ft_strlen, ft_strdup, ft_strcpy, ft_strncpy, ft_strcat, ft_strncat, ft_strlcat, ft_strchr, ft_strrchr, ft_strstr, ft_strnstr, ft_strcmp, ft_strncmp

Character checks and transformations: ft_isalpha, ft_isdigit, ft_isalnum, ft_isascii, ft_isprint, ft_toupper, ft_tolower

Output functions: ft_putchar, ft_putstr, ft_putendl, ft_putnbr
And many more.

## Installation
```sh
git clone https://github.com/Asrasal47/42-Libft.git
cd Libft
make
```
This will compile the library and generate a libft.a file.


## Usage
Include the header file (libft.h) in your C project:
>#include "libft.h"

When compiling your project, link with the libft.a file:
gcc your_c_file.c -L. -lft -o your_program_name

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
