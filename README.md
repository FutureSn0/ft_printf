
# ft_printf

ft_printf is a project where we learn about varadic arguments in C by recreating the printf function included in <stdout.h>. ft_printf operates the same way as printf and can be used to output strings, integers and hex values. 

# How to use

1. Clone the repository, then enter the cloned directory

```bash
git clone git@github.com:FutureSn0/ft_printf.git
cd ft_printf
```

2. Run "make"

```bash
make
```

3. include the ft_printf header in you code in order to use the function

```bash
#include "ft_printf.h"
```
There are some cases where you may want to manually compile some files. Inlcude a path to the libft.a file in your bash command.

```bash
gcc <source files> ft_printf/libftprintf.a
```

Additional makefile rules

`make` - Compile ft_printf files.

`make clean` - Delete all .o (object files) files.

`make fclean` - Delete all .o (object file) and .a (executable) files.

`make re` - Reblilds project by using rules `fclean` + `all`.

# Subject
### Mandatory
 - %c - Print a single character;
 - %s - Print a string;
 - %p - Print void * pointer argument in hexadecimal format;
 - %d - Print a decimal (base 10) number;
 - %i - Print an integer in base 10;
 - %u - Prints an unsigned decimal (base 10) number;
 - %x - Print a number in hexadecimal (base 16) lowercase format;
 - %X - Print a number in hexadecimal (base 16) uppercase format;
 - %% - Print a percentage sign;

All functions must be fully functioning and well-tested to obtain passing score (100/100).

# Norminette

All projects are written according to a standard implemented by the 42 school known as "Norminette". This standard specifies our files to be formatted in a specific way, limits the amount of functions and varables included in a single file, and also the use of certain statements (for, do.. while, switch.. case, etc).
