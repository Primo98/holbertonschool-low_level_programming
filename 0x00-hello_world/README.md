_10/February/2022_


__"My first programming with the C language"__



"The following commands that make up the executable Scripts;"" __WRITE THEM WITHOUT THE FIRST AND LAST PARENTHESES!__"



**0-preprocessor** (gcc -E $CFILE -o c)

_Write a script that runs a C file through the preprocessor and save the result into another file._

_a) The C file name will be saved in the variable $CFILE_
_b) The output should be saved in the file c_

**1-compiler** (gcc -c $CFILE)

_Write a script that compiles a C file but does not link._

_a) The C file name will be saved in the variable $CFILE_
_b) The output file should be named the same as the C file, but with the extension .o instead of .c._
_c) Example: if the C file is main.c, the output file should be main.o_

**2-assembler** (gcc -S $CFILE)

_Write a script that generates the assembly code of a C code and save it in an output file._

_a) The C file name will be saved in the variable $CFILE_
_b) The output file should be named the same as the C file, but with the extension .s instead of .c._
_c) Example: if the C file is main.c, the output file should be main.s_

**3-name** (gcc $CFILE -o cisfun)

_Write a script that compiles a C file and creates an executable named cisfun._

_a) The C file name will be saved in the variable $CFILE_