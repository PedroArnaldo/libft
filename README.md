# LIBFT

* [Introduction](#introduction)
* [Part 01](#part_1)
* [Part 02](#part_2)
* [Make](#make)

## Introduction

Libft is a project for standard C library override functions.


### Part 01

| [**ft\_isalpha**](https://github.com/PedroArnaldo/libft/blob/main/ft_isalpha.c) | checks for an alphabetic character.| <br>
| [**ft\_isdigit**](https://github.com/PedroArnaldo/libft/blob/main/ft_isdigit.c) | checks for a digit (0 through 9).| <br>
| [**ft\_isalnum**](https://github.com/PedroArnaldo/libft/blob/main/ft_isalnum.c) | checks for an alphanumeric character.| <br>
| [**ft\_isascii**](https://github.com/PedroArnaldo/libft/blob/main/ft_isascii.c) | checks whether c is a 7-bit unsigned char value that fits into the ASCII character set.| <br>
| [**ft\_isprint**](https://github.com/PedroArnaldo/libft/blob/main/ft_isprint.c) |checks for any printable character including space.| <br>
| [**ft\_strlen**](https://github.com/PedroArnaldo/libft/blob/main/ft_strlen.c) | returns the length of the string s. | <br>
| [**ft\_memset**](https://github.com/PedroArnaldo/libft/blob/main/ft_memset.c) | fills the first n bytes of the memory area pointed to by s with the constant byte c.| <br>
| [**ft\_bzero**](https://github.com/PedroArnaldo/libft/blob/main/ft_bezero.c) | erases the data in the n bytes of the memory starting at the location pointed to by s, by writing zeros to that area.| <br>
| [**ft\_memcpy**](https://github.com/PedroArnaldo/libft/blob/main/ft_memcpy.c) | copies n bytes from memory area src to memory are dest. The memory ares must not overlap.| <br>
| [**ft\_memmove**](https://github.com/PedroArnaldo/libft/blob/main/ft_memmove.c) | copies n bytes from memory area src to memory area dest. The two strings may overlap.| <br>
| [**ft\_strlcpy**](https://github.com/PedroArnaldo/libft/blob/main/ft_strlcpy.c) | copies up to size - 1 characters from the NULL-terminatedstring src to dst, NULL-terminating the result.| <br>
| [**ft\_strlcat**](https://github.com/PedroArnaldo/libft/blob/main/ft_strlcat.c) | appends the NUL-terminated string src to the end of dst. It will append at most size - strlen(dst) - 1 byte, NUL-terminating the result.| <br>
| [**ft\_toupper**](https://github.com/PedroArnaldo/libft/blob/main/ft_toupper.c) | convert lowercase letters to uppercase.| <br>
| [**ft\_tolower**](https://github.com/PedroArnaldo/libft/blob/main/ft_tolower.c) | convert uppercase letters to lowercase.| <br>
| [**ft\_strchr**](https://github.com/PedroArnaldo/libft/blob/main/ft_strchr.c) | returns a pointer to the first occurrence of the characterc in the string s.| <br>
| [**ft\_strrchr**](https://github.com/PedroArnaldo/libft/blob/main/ft_strrchr.c) | returns a pointer to the last occurrence of the character c in the string s.| <br>
| [**ft\_strncmp**](https://github.com/PedroArnaldo/libft/blob/main/ft_strncmp.c) | lexicographically compares the null-terminated strings s1 and s2. function not more than len characters. Return an integer greater than, equal to, or less than 0, according as the string s1 is greater than, equal to, orless than the string s2. The comparison is done using unsingned characters, so that '\200' is greater than '\0'.| <br>
| [**ft\_memchr**](https://github.com/PedroArnaldo/libft/blob/main/ft_memchr.c) | scans the initial n bytes of the memory area pointed to bys for the first instance of c.| <br>
| [**ft\_memcmp**](https://github.com/PedroArnaldo/libft/blob/main/ft_memcmp.c) | function compares the first n bytes (each interpreted as unsigned char) of the memory areas s1 and s2.| <br>
| [**ft\_strnstr**](https://github.com/PedroArnaldo/libft/blob/main/ft_strnstr.c) | locates the first occurence of the null-terminated string little in the string big, where not more than len characters are searched.| <br>
| [**ft\_atoi**](https://github.com/PedroArnaldo/libft/blob/main/ft_atoi.c) | converts the initial portion of the string pointed to by str to int representation and returns the int.| <br>
| [**ft\_calloc**](https://github.com/PedroArnaldo/libft/blob/main/ft_calloc.c) | allocates memory for an array of nmemb elements of size bytes each and returns a pointer to the allocated memory. The memory is set to zero.| <br>
| [**ft\_strdup**](https://github.com/PedroArnaldo/libft/blob/main/ft_strdup.c) | returns a pointer to a new string which is a duplicate of the string s.| <br>

### Part 02

| [**ft\_substr**](https://github.com/PedroArnaldo/libft/blob/main/ft_substr.c) | returns the substring of the given start position with thegiven lenght or smaller if the length of the original string is less than start + length.| <br>
| [**ft\_strjoin**](https://github.com/PedroArnaldo/libft/blob/main/ft_strjoin.c) | combines all strings in the argument lis, and puts the result into the returned string with dynamically allocated memory. The returned string is separated by the delimiter specified by the first argument separator. The dynamically allocated memory needs to be freed by the user.| <br>
| [**ft\_strtrim**](https://github.com/PedroArnaldo/libft/blob/main/ft_strtrim.c) | removes all whitespace characters from the beginning and the end of a string. | <br>
| [**ft\_split**](https://github.com/PedroArnaldo/libft/blob/main/ft_split.c) | Allocates and returns an array of strings obtained by splitting ’s’ using the character ’c’ as a delimiter. The array must end with a NULL pointer.| <br>
| [**ft\_itoa**](https://github.com/PedroArnaldo/libft/blob/main/ft_itoa.c) | Allocates and returns a string representing the integer received as an argument. Negative numbers must be handled.| <br>
| [**ft\_strmapi**](https://github.com/PedroArnaldo/libft/blob/main/ft_strmapi.c) | Applies the function ’f’ to each character of the string ’s’, and passing its index as first argument to create a new string resulting from successive applications of ’f’.| <br>
| [**ft\_striteri**](https://github.com/PedroArnaldo/libft/blob/main/ft_iteri.c) | Applies the function ’f’ on each character of the string passed as argument, passing its index as first argument. Each character is passed by address to ’f’ to be modified if necessary.| <br>
| [**ft\_putchar\_fd**](https://github.com/PedroArnaldo/libft/blob/main/ft_putchar_fd.c) | Outputs the character ’c’ to the given file descriptor.| <br>
| [**ft\_putstr\_fd**](https://github.com/PedroArnaldo/libft/blob/main/ft_putchar_fd.c) | Outputs the string ’s’ to the given file descriptor.| <br>
| [**ft\_putendl_fd**](https://github.com/PedroArnaldo/libft/blob/main/ft_putendl_fd.c) | Outputs the string ’s’ to the given file descriptor followed by a newline.| <br>
| [**ft\_putnbr\_fd**](https://github.com/PedroArnaldo/libft/blob/main/ft_putnbr_fd.c) | Outputs the integer ’n’ to the given file descriptor.| <br>

## Make

| `make` | creates .o files for each function as well as the main library file, libft.a | <br>
| `make clean` | removes the .o files used to create the library | <br>
| `make fclean` | removes the .o & .a files used to create the library | <br>
| `make re` | removes all .o & .a files then remakes them | <br>

