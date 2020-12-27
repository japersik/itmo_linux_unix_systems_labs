Задание
```
Lab 09 (till 04 december)
1. Connect using ftp with ftp.scientificlinux.org
   (as anonymous with the same password)
2. Change to directory "linux/scientific",
   Save the content (list) of this directory to file "Lab09.test"
   in home directory
3. What latest version of '7.X' distributive?
   Display this version in your terminal (only version on the line).
4. Using 'ncat' command output the HTML content from 'ifmo.ru' to terminal
   and save 12 first lines of respond to file "Lab09NCAT.test".
   in home directory.
```
Порядок выполнения команд:
```
ftp ftp.scientificlinux.org
anonymous
pass
cd linux/scientific 
ls 
ls . ~/Lab09.test
bye 
awk '{print $9}' ~/Lab09.test |grep '7\.' |tail -1
head -n 12 ~/Lab09NCAT1.test > ~/Lab09NCAT.test
printf "GET / HTTP/1.0\r\n\r\n" | ncat ifmo.ru 80 | head -n 12 > Lab09NCAT.test
```