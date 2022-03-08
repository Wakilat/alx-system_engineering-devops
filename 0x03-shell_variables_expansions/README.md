#!/bin/bash
0.Create a script that creates an alias.
alias ls="rm *"
1. Create a script that prints hello user, where user is the current Linux user.
echo "hello $USER"
2. Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
PATH=$PATH:/action
3. Create a script that counts the number of directories in the PATH
echo $PATH | tr ":" "\n" | wc -l
