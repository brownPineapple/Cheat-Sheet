#  How to start a bash script

```bash
#!/bin/bash   #Tell the interpreter that this is a bash script
#!/usr/bin/env bash -> Same as above, safer by creating an env
```

##  Print something on screen
```bash
echo "Hello World!"
printf "Hello World!"
```
##  If - Else - Elif
```bash
if [ condition ]; then
    Commands
else
    Commands
fi`
```
### Elif is used to check for multiple conditions
```bash
if [ condition1 ]; then; 
  Commands
elif [ condition2 ]
  Commands
else:
  Commands
fi
```
### example:
```bash
a=10;b=20; # declaration

if [ $a -eq $b ]; then
    echo "they are equal"
elif [ $a > $b ]
    echo "$a is greater than $b"
else
    echo "$b is greater than $a"
fi
```
## User Input
```bash
read -p "What is your name? " name
echo "Enjoy this tutorial, $name"
```
##  Loops

### While Loop:
```bash
x=1;
while [ $x -le 5 ]; do
  echo "Hello World"
  ((x=x+1))
done
```
### Until loop:
```bash
echo -e "\nUntil Loop"
declare -i m=0
until (( m == 10 )); do
    echo "m:$m"
    (( m++ ))
done
```
# More at - https://github.com/brownPineapple/hello-world/blob/master/Bash%20Scripting%20cheatsheet.md
