# Cheat-Sheet

This is a collection of linux commands.

How to start a bash script

#!/bin/bash   #Tell the interpreter that this is a bash script
#!/usr/bin/env bash -> Same as above, safer by creating an env

Print something on screen

echo "Hello World!"
printf "Hello World!"

If - Else - Elif

if [ condition ]; then
    Commands
else
    Commands
fi

Elif is used to check for multiple conditions

if [ condition1 ]; then; 
  Commands
elif [ condition2 ]; then
  Commands
else:
  Commands
fi

example:

a=10;b=20; # declaration

if [ $a -eq $b ]; then
    echo "they are equal"
elif [ $a > $b ]
    echo "$a is greater than $b"
else
    echo "$b is greater than $a"
fi



