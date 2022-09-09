1. Write a script that runs a C file through the preprocessor and save the result into another file.
	#!/bin/bash
	gcc -E $CFILE -o c
2. Write a script that compiles a C file but does not link.
	#!/bin/bash
	gcc -c $FILE
3. script that generates the assembly code of a C code and save it in an output file with ext .s
	#!/bin/bash
	gcc -S $CFILE 
4. Write a script that compiles a C file and creates an executable named cisfun.
	#!/bin/bash
	gcc $CFILE -o cisfun

