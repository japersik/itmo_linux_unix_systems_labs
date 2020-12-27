Задание
```
Lab 12 (till 11 december)

1. Write a script 'Lab12-1' that copies all files with extenion 'jpeg'
   to files with extension 'jpg' in the directory specified by the argument.
   Run it for directory 'Test12'.
   Use 'ls' command to output the content of 'Test12'
2. Write a script 'Lab12-2' that outputs the base name of the files
   in direcitory specified by argument, or in home directory, if not specified.
   Run it to print base name for files in the directory Test12
3. Modify the script 'Lab12-2' (new name 'Lab12-3'). This script should print
   the base name without extension of files in the directory, specified by
   first argument and with extension, specified by second argument (with dot).
   Run it with arguments: directory 'Test12' and extension '.jpeg'.
4. Modify 'Lab12-3' script by defining the 'usage' function,
   which is called if 'Lab12-4' is running without arguments or
   no files with specified argument exists. Usage function should print
   'usage: Lab12-4 ...'. Demonstrate how it works.
```
Порядок выполнения команд:
```
 ./Lab12-1 Test12
  ls Test12
 ./Lab12-2 Test12
 ./Lab12-3 Test12 .jpeg
 ./Lab12-4 Test12 .jpeg
 ./Lab12-4 
```
