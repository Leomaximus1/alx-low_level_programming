1. Write a script that runs a C file through the preprocessor and save the result into another file.
	#!/bin/bash
	gcc -E $CFILE -o c
2. Write a script that compiles a C file but does not link.
	#!/bin/bash
	gcc -c $FILE
