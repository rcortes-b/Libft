<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/byaliego/42-project-badges/main/badges/libftm.png" width="150" />
<br>Libft</h1>
<h3>◦ A useful library for 42 School</h3>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📂 repository Structure](#-repository-structure)
- [⚙️ Modules](#modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Use Libft](#-use-Libft)
    - [🧪 Tests](#-tests)
- [🛣 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---

## 📍 Overview

The `Libft` project is about creating a C library of implementations of the original standard C library functions.


---


## ⚙️ Modules

<details closed><summary>Root</summary>

| File                                                                                           | Summary       |
| ---                                                                                            | ---           |
| [libft.h](https://github.com/San-tito/Libft/blob/main/libft.h)                                 | Header file with function prototypes |im
| [Makefile](https://github.com/San-tito/Libft/blob/main/Makefile)                               | Makefile for compiling the library |

</details>


<details closed><summary>Libc functions</summary>

| File                                                                                           | Summary       |
| ---                                                                                            | ---           |
| [ft_toupper.c](https://github.com/San-tito/Libft/blob/main/ft_toupper.c)                       | Convert character to uppercase |
| [ft_tolower.c](https://github.com/San-tito/Libft/blob/main/ft_tolower.c)                       | Convert character to uppercase |
| [ft_strrchr.c](https://github.com/San-tito/Libft/blob/main/ft_strrchr.c)                       | Locate character in string from the end |
| [ft_strnstr.c](https://github.com/San-tito/Libft/blob/main/ft_strnstr.c)                       | Locate substring in string |
| [ft_strncmp.c](https://github.com/San-tito/Libft/blob/main/ft_strncmp.c)                       | Compare two strings up to a specified number of characters |
| [ft_strlen.c](https://github.com/San-tito/Libft/blob/main/ft_strlen.c)                         | Calculate the length of a string |
| [ft_strlcpy.c](https://github.com/San-tito/Libft/blob/main/ft_strlcpy.c)                       | Copy a string to a specified size |
| [ft_strlcat.c](https://github.com/San-tito/Libft/blob/main/ft_strlcat.c)                       | Concatenate strings with a specified size |
| [ft_strdup.c](https://github.com/San-tito/Libft/blob/main/ft_strdup.c)                         | Duplicate a string with malloc |
| [ft_strchr.c](https://github.com/San-tito/Libft/blob/main/ft_strchr.c)                         | Locate character in string |
| [ft_memset.c](https://github.com/San-tito/Libft/blob/main/ft_memset.c)                         | Fill memory with a constant byte |
| [ft_memmove.c](https://github.com/San-tito/Libft/blob/main/ft_memmove.c)                       | Copy memory area |
| [ft_memcpy.c](https://github.com/San-tito/Libft/blob/main/ft_memcpy.c)                         | Copy memory area |
| [ft_memcmp.c](https://github.com/San-tito/Libft/blob/main/ft_memcmp.c)                         | Compare memory areas |
| [ft_memchr.c](https://github.com/San-tito/Libft/blob/main/ft_memchr.c)                         | Locate byte in byte string |
| [ft_isprint.c](https://github.com/San-tito/Libft/blob/main/ft_isprint.c)                       | Check if a character is printable |
| [ft_isdigit.c](https://github.com/San-tito/Libft/blob/main/ft_isdigit.c)                       | Check if a character is a digit |
| [ft_isascii.c](https://github.com/San-tito/Libft/blob/main/ft_isascii.c)                       | Check if a character is an ASCII character |
| [ft_isalpha.c](https://github.com/San-tito/Libft/blob/main/ft_isalpha.c)                       | Check if a character is an alphabet character |
| [ft_isalnum.c](https://github.com/San-tito/Libft/blob/main/ft_isalnum.c)                       | Check if a character is alphanumeric |
| [ft_calloc.c](https://github.com/San-tito/Libft/blob/main/ft_calloc.c)                         | Allocate and zero-initialize array |
| [ft_bzero.c](https://github.com/San-tito/Libft/blob/main/ft_bzero.c)                           | Set a byte string to zero |
| [ft_atoi.c](https://github.com/San-tito/Libft/blob/main/ft_atoi.c)                             | Convert a string to an integer |

</details>

<details closed><summary>Additional functions</summary>

| File                                                                                           | Summary       |
| ---                                                                                            | ---           |
| [ft_substr.c](https://github.com/San-tito/Libft/blob/main/ft_substr.c)                         | Extract substring from string |
| [ft_strjoin.c](https://github.com/San-tito/Libft/blob/main/ft_strjoin.c)                       | Concatenate two strings |
| [ft_strtrim.c](https://github.com/San-tito/Libft/blob/main/ft_strtrim.c)                       | Trim leading and trailing a character from a string|
| [ft_split.c](https://github.com/San-tito/Libft/blob/main/ft_split.c)                           | Split a string into an array of substrings |
| [ft_itoa.c](https://github.com/San-tito/Libft/blob/main/ft_itoa.c)                             | Convert an integer to a string |
| [ft_strmapi.c](https://github.com/San-tito/Libft/blob/main/ft_strmapi.c)                       | Apply a function to each character of a string |
| [ft_striteri.c](https://github.com/San-tito/Libft/blob/main/ft_striteri.c)                     | Apply a function to each character of a string with its index |
| [ft_putstr_fd.c](https://github.com/San-tito/Libft/blob/main/ft_putstr_fd.c)                   | Output a string to a file descriptor |
| [ft_putnbr_fd.c](https://github.com/San-tito/Libft/blob/main/ft_putnbr_fd.c)                   | Output an integer to a file descriptor |
| [ft_putendl_fd.c](https://github.com/San-tito/Libft/blob/main/ft_putendl_fd.c)                 | Output a string to a file descriptor, followed by a newline |
| [ft_putchar_fd.c](https://github.com/San-tito/Libft/blob/main/ft_putchar_fd.c)                 | Output a character to a file descriptor |

</details>

<details closed><summary>Bonus</summary>

| File                                                                                           | Summary       |
| ---                                                                                            | ---           |
| [ft_lstsize_bonus.c](https://github.com/San-tito/Libft/blob/main/ft_lstsize_bonus.c)           | Count the number of elements in a list |
| [ft_lstnew_bonus.c](https://github.com/San-tito/Libft/blob/main/ft_lstnew_bonus.c)             | Create a new list element |
| [ft_lstmap_bonus.c](https://github.com/San-tito/Libft/blob/main/ft_lstmap_bonus.c)             | Apply a function to each element of a list and create a new list |
| [ft_lstlast_bonus.c](https://github.com/San-tito/Libft/blob/main/ft_lstlast_bonus.c)           | Return the last element of a list |
| [ft_lstiter_bonus.c](https://github.com/San-tito/Libft/blob/main/ft_lstiter_bonus.c)           | Apply a function to each element of a list |
| [ft_lstdelone_bonus.c](https://github.com/San-tito/Libft/blob/main/ft_lstdelone_bonus.c)       | Delete a list element |
| [ft_lstclear_bonus.c](https://github.com/San-tito/Libft/blob/main/ft_lstclear_bonus.c)         | Delete and free a list |
| [ft_lstadd_front_bonus.c](https://github.com/San-tito/Libft/blob/main/ft_lstadd_front_bonus.c) | Add a new element at the beginning of the list |
| [ft_lstadd_back_bonus.c](https://github.com/San-tito/Libft/blob/main/ft_lstadd_back_bonus.c)   | Add a new element at the end of the list |

</details>

---

## 🚀 Getting Started

### 🔧 Installation

1. Clone the Libft repository:
```sh
git clone https://github.com/San-tito/Libft
```

2. Change to the project directory:
```sh
cd Libft
```

3. Compile the dependencies:
```sh
make
```

### 🤖 Use Libft
Once the library is successfully compiled, you can use it in your projects. Link the `libft.a` file to your program, and include the `libft.h` header in your source files.
To compile your program with Libft, use:
```sh
gcc -o my_program my_program.c -L . -lft
```

---

## 👏 Acknowledgments

- [Master Memory Management](https://medium.com/p/b86fedd39b96)
- [Libft - C Standard Library Rewrite](https://www.asidesigned.com/project-libft.html)
- [libftTester](https://github.com/Tripouille/libftTester)

[**Return**](#Top)

---
