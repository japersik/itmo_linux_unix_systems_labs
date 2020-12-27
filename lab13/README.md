Задание
```
Lab 13 (till 18 december)

1. Write a script 'Lab13-1' that use command 'lsblk'.
   Your script should display the partition name, type and size of
   largest partition of device specified by first argument.
   For example: 'Lab13-1 /dev/sda' yields 'sda1 part 1234567890'.
2. Write a script 'Lab13-2' that prints the total space usage
   for elements, specified by arguments. 'Lab13-2' should output
   one line for elements: 'size elements' Redirect error output to '/dev/null'.
   Run it for two elements: home directory and /tmp
3. Write a script 'Lab13-3' that prints available disk space
   for elements, specified by arguments. 'Lab13-3' should output
   one line for elements: 'file_system mount_point available_space'.
   Run it for two elements: home directory and /tmp
```
Порядок выполнения команд:
```
./Lab13-1 /dev/sda
./Lab13-2 /home/user /tmp
./Lab13-3 /home/user /tmp
```
