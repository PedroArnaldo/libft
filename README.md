# LIBFT

* [Introduction](#introduction)
* [Part 01](#part_1)
* [Part 02](#part_2)
* [Make](#make)

## Introduction

Libft is a project for standard C library override functions.


### Part 01

| --- | --- |
| [**ft\_isalpha**]() | checks for an alphabetic character.|
| [**ft\_isdigit**]() | checks for a digit (0 through 9).|
| [**ft\_isalnum**]() | checks for an alphanumeric character.|
| [**ft\_isascii**]() | checks whether c is a 7-bit unsigned char value that fits into the ASCII character set.|
| [**ft\_isprint**]() |checks for any printable character including space.|
| [**ft\_strlen**]()| returns the length of the string s. |
| [**ft\_memset**]() | fills the first n bytes of the memory area pointed to by s with the constant byte c.|
| [**ft\_bzero**]() | erases the data in the n bytes of the memory starting at the location pointed to by s, by writing zeros to that area.|
| [**ft\_memcpy**]() | copies n bytes from memory area src to memory are dest. The memory ares must not overlap.|
| [**ft\_memmove**]() | copies n bytes from memory area src to memory area dest. The two strings may overlap.|
| [**ft\_strlcpy**]() | copies up to size - 1 characters from the NULL-terminatedstring src to dst, NULL-terminating the result.|
| [**ft\_strlcat**]() | appends the NUL-terminated string src to the end of dst. It will append at most size - strlen(dst) - 1 byte, NUL-terminating the result.|
| [**ft\_toupper**]() | convert lowercase letters to uppercase.|
| [**ft\_tolower**]() | convert uppercase letters to lowercase.|
| [**ft\_strchr**]() | returns a pointer to the first occurrence of the characterc in the string s.|
| [**ft\_strrchr**]() | returns a pointer to the last occurrence of the character c in the string s.|
| [**ft\_strncmp**]() | lexicographically compares the null-terminated strings s1 and s2. function not more than len characters. Return an integer greater than, equal to, or less than 0, according as the string s1 is greater than, equal to, orless than the string s2. The comparison is done using unsingned characters, so that '\200' is greater than '\0'.|
| [**ft\_memchr**]() | scans the initial n bytes of the memory area pointed to bys for the first instance of c.|
| [**ft\_memcmp**]() | function compares the first n bytes (each interpreted as unsigned char) of the memory areas s1 and s2.|
| [**ft\_strnstr**]() | locates the first occurence of the null-terminated string little in the string big, where not more than len characters are searched.|
| [**ft\_atoi**]() | converts the initial portion of the string pointed to by str to int representation and returns the int.|
| [**ft\_calloc**]() | allocates memory for an array of nmemb elements of size bytes each and returns a pointer to the allocated memory. The memory is set to zero.|
| [**ft\_strdup**]() | returns a pointer to a new string which is a duplicate of the string s.|

### Part 02

| --- | ---|
| [**ft\_substr**]() | returns the substring of the given start position with thegiven lenght or smaller if the length of the original string is less than start + length.|
| [**ft\_strjoin**]() | combines all strings in the argument lis, and puts the result into the returned string with dynamically allocated memory. The returned string is separated by the delimiter specified by the first argument separator. The dynamically allocated memory needs to be freed by the user.|
| [**ft\_strtrim**]() | removes all whitespace characters from the beginning and the end of a string. |
| [**ft\_split**]() | Allocates and returns an array of strings obtained by splitting ’s’ using the character ’c’ as a delimiter. The array must end with a NULL pointer.|
| [**ft\_itoa**]() | Allocates and returns a string representing the integer received as an argument. Negative numbers must be handled.|
| [**ft\_strmapi**]() | Applies the function ’f’ to each character of the string ’s’, and passing its index as first argument to create a new string resulting from successive applications of ’f’.|
| [**ft\_striteri**]() | Applies the function ’f’ on each character of the string passed as argument, passing its index as first argument. Each character is passed by address to ’f’ to be modified if necessary.|
| [**ft\_putchar\_fd**]() | Outputs the character ’c’ to the given file descriptor.|
| [**ft\_putstr\_fd**]() | Outputs the string ’s’ to the given file descriptor.|
| [**ft\_putendl_fd**]() | Outputs the string ’s’ to the given file descriptor followed by a newline.|
| [**ft\_putnbr\_fd**]() | Outputs the integer ’n’ to the given file descriptor.|

## Make

| --- | --- |
| `make` | creates .o files for each function as well as the main library file, libft.a |
| `make clean` | removes the .o files used to create the library |
| `make fclean` | removes the .o & .a files used to create the library |
| `make re` | removes all .o & .a files then remakes them |

