## Environmental Variables
Temporary setup
```sh
set #Displays all the environmental variables
set varname #Display the value of the variable varname
set varname=value #Set or change the valeu of varname
```
Presistant setup
```sh
setx varname value #Set or change the valeu of varname
```
Use Env var to change directory (find the aws credential file) 
```sh
cd "%UserProfile%\.aws"

```
Change directory to env variable 
```sh
cd %ENV_VARIABLE%
```


## Basic Commands
```sh

dir #ls
start . #opens the pwd folder

findstr name #grep
  -i: not case-sensitive
  
type file.txt #cat

del file.txt #rm Remove file
rmdir dir #rm Remove directory
```

## Hotkeys
F3: Print the previous command
F7: Get the history in a list where you can choose any previous command

## Setup VS code 
Add the following to the path variable and run code to open pwd folder in VS
  C:\Users\username\AppData\Local\Programs\Microsoft VS Code\bin
