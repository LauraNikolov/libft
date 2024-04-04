# LIBFT

## 42 Project

Replica of these libc functions: 

• isalpha
• isdigit
• isalnum
• isascii
• isprint
• strlen
• memset
• bzero
• memcpy
• memmove
• strlcpy
• strlcat
• toupper
• tolower
• strchr
• strrchr
• strncmp
• memchr
• memcmp
• strnstr
• atoi 
• calloc
• strdup

and some supplementary functions :

| Function name | ft_substr |
| :------------ | :-------- |
| Prototype | ```char *ft_substr(char const *s, unsigned int start, unsigned int len)``` | 
| Parameters | s: The string from which to extract the new string. start: The start index of the new string in the string 's'. len: The maximum size of the new string | 
| Return value | The new string. NULL is allocation failed. |
| Description | Allocate (with malloc) and return a string from the 's' string. This new string starts at the 'start' index and has for maximal size 'len'. | 

| Function name | ft_strjoin |
| :------------ | :-------- |
| Parameters |  | s1: The prefix string. s2: The suffix string. | 
| Return value | The new string. NULL is allocation failed. |
| Description | Allocate (with malloc) and return a string from the 's' string. This new string starts at the 'start' index and has for maximal size 'len'. | 

