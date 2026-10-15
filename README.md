# Libft

Libft is a C library developed as part of the 42 school curriculum. It brings together reimplementations of common libc functions and utilities for working with strings, memory, and linked lists.

## Contents

- Character manipulation and conversion functions
- Memory management functions
- String manipulation functions
- Functions for writing to a file descriptor
- Bonus: utilities for creating, traversing, and freeing linked lists (`t_list`)

## Build

From the repository root, build the main library:

```sh
make -C libft
```

To add the bonus functions to the archive:

```sh
make -C libft bonus
```

The build produces the static archive `libft/libft.a`, which can be reused and linked into a C project. Function prototypes are declared in `libft/libft.h`.

## Cleanup

```sh
make -C libft clean   # remove object files
make -C libft fclean  # remove object files and the archive
make -C libft re      # rebuild the main library
```
