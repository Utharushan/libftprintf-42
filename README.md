# ft_printf

This project is a custom implementation of the `printf` function in C, created as part of the **42** curriculum. It aims to help students understand how formatted output functions work by replicating `printf` functionality with a limited set of format specifiers.

## Purpose

The goal of the **ft_printf** project is to recreate a simplified version of the standard `printf` function, which takes a format string and a variable number of arguments to produce formatted output.

## Features

This implementation supports the following format specifiers:

- `%c` – Character
- `%s` – String
- `%d` – Integer
- `%i` – Integer (same as `%d`)
- `%u` – Unsigned integer
- `%x` – Unsigned hexadecimal (lowercase)
- `%X` – Unsigned hexadecimal (uppercase)
- `%p` – Pointer address
- `%%` – Percent sign

Additionally, the project focuses on:

- Managing variable argument lists (`va_list`)
- Handling different data types
- Formatting and aligning output
- Correct memory management and error handling
