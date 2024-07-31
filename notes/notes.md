# BASH course 

# Introduction concept

* `pwd` ~ print working directory 

* `#!/bin/bash` shebang, tell the script which shell to use 

* `chmod +x` to give the permission to run the script

* `ls -l` -l is called a flag

--- 

## Variable

* `VARIABLE_NAME=Value` this is how we define a variable name,capital letters. We add `$` before the variable when we call it in a function. 


## User input

- `read VARIABLE_NAME` whill take the use input and store it in VARIABLE_NAME.

## Positional argument 

- Argument that are in specific position starting from 1, while 0 is reserved for the shell. 
- e.g. `echo hello $1 $2`. When running the script `./pos_arg.sh Ibrahim Alghrabi` it will take the arguments and assign them to their respective order number.  
- You can provide extra arguemnt and it wont show any error. 

## Output/Input redirection: 

### Piping | 

- 
