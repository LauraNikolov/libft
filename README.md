# LIBFT

## 42 Project

Replica of these libc functions: 

- isalpha  
- isdigit  
- isalnum  
- isascii  
- isprint  
- strlen  
- memset  
- bzero  
- memcpy  
- memmove  
- strlcpy  
- strlcat  
- toupper  
- tolower  
- strchr  
- strrchr  
- strncmp  
- memchr  
- memcmp  
- strnstr  
- atoi  
- calloc  
- strdup  

and some supplementary functions:

---

| Function name | ft_substr |
|--------------|-----------|
| Prototype | `char *ft_substr(char const *s, unsigned int start, unsigned int len)` |
| Parameters | `s`: The string from which to extract the new string. `start`: The start index. `len`: The maximum length of the new string. |
| Return value | The new string. NULL if allocation fails. |
| Description | Allocates (with malloc) and returns a substring from `s`. The substring begins at index `start` and is at most `len` characters long. |

---

| Function name | ft_strjoin |
|--------------|------------|
| Prototype | `char *ft_strjoin(char const *s1, char const *s2)` |
| Parameters | `s1`: The prefix string. `s2`: The suffix string. |
| Return value | The new string. NULL if allocation fails. |
| Description | Allocates (with malloc) and returns a new string, the result of concatenation of `s1` and `s2`. |

---

| Function name | ft_strtrim |
|--------------|------------|
| Prototype | `char *ft_strtrim(char const *s1, char const *set)` |
| Parameters | `s1`: The string to trim. `set`: The set of characters to remove. |
| Return value | The trimmed string. NULL if allocation fails. |
| Description | Allocates (with malloc) and returns a copy of `s1` with characters in `set` removed from the beginning and the end. |

---

| Function name | ft_split |
|--------------|----------|
| Prototype | `char **ft_split(char const *s, char c)` |
| Parameters | `s`: The string to split. `c`: The delimiter character. |
| Return value | An array of new strings resulting from the split. NULL if allocation fails. |
| Description | Allocates (with malloc) and returns an array of strings obtained by splitting `s` using the delimiter `c`. The array is NULL-terminated. |

---

| Function name | ft_itoa |
|--------------|---------|
| Prototype | `char *ft_itoa(int n)` |
| Parameters | `n`: The integer to convert. |
| Return value | The string representing the integer. NULL if allocation fails. |
| Description | Allocates (with malloc) and returns a string representing the integer `n`. Handles negative numbers as well. |

---

| Function name | ft_strmapi |
|--------------|------------|
| Prototype | `char *ft_strmapi(char const *s, char (*f)(unsigned int, char))` |
| Parameters | `s`: The input string. `f`: The function to apply to each character with its index. |
| Return value | The new string resulting from the successive applications of `f`. NULL if allocation fails. |
| Description | Applies function `f` to each character of the string `s`, passing its index as the first argument, and returns a new string. |

---

| Function name | ft_striteri |
|--------------|-------------|
| Prototype | `void ft_striteri(char *s, void (*f)(unsigned int, char *))` |
| Parameters | `s`: The string to iterate. `f`: The function to apply to each character with its index. |
| Return value | None. |
| Description | Applies the function `f` to each character of the string `s`, passing its index and a pointer to the character. Modifies the string in place. |

---

| Function name | ft_putchar_fd |
|--------------|----------------|
| Prototype | `void ft_putchar_fd(char c, int fd)` |
| Parameters | `c`: The character to write. `fd`: The file descriptor. |
| Return value | None. |
| Description | Outputs the character `c` to the given file descriptor. |

---

| Function name | ft_putstr_fd |
|--------------|---------------|
| Prototype | `void ft_putstr_fd(char *s, int fd)` |
| Parameters | `s`: The string to write. `fd`: The file descriptor. |
| Return value | None. |
| Description | Outputs the string `s` to the given file descriptor. |

---

| Function name | ft_putendl_fd |
|--------------|----------------|
| Prototype | `void ft_putendl_fd(char *s, int fd)` |
| Parameters | `s`: The string to write. `fd`: The file descriptor. |
| Return value | None. |
| Description | Outputs the string `s` followed by a newline to the given file descriptor. |

---

