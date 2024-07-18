# Get_next_line
The goal of this project is to create the function get_next_line.c_ which, when called in a loop, will then allow the available text in the file descriptor to be read one line at a time until the end of the file. The program can compile with the flag-D BUFFER_SIZE=xx which will be used as the buffer size for the read calls in get_next_line, if the buffer size is not specified a default one is set.

## USAGE
To use this function in your code, simply include it in your header file such as:
```
#include "get_next_line.h"
```
Then Compile it next to your code
```
gcc your_main.c get_next_line.c get_next_line.h
```
