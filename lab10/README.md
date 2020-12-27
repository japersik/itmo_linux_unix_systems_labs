Задание
```
Lab 10 (till 04 december)

1. Use the command 'lynx' to get formatted output
   (named 'Test10lynx.txt') from ifmo.ru in text mode.
   Type size of 'Test10lynx.txt'.
2. Use the command 'wget' to download from 'ifmo.ru' the file
   you get by default (rename it to 'Test10.html')
3. Use command 'ssh' to login in localhost, do something and logout
   (use an account you know)
4. Copy (using 'scp') the file '~/.bash_history'
   from localhost to '/tmp' directory.
5. Use the command 'rsync' to copy file '.bashrc' located in home directory
   to '/tmp' directory. Compare two files

```
Порядок выполнения команд:
```
lynx -dump ifmo.ru > Test10lynx.txt

ls -l  Test10lynx.txt | awk '{ print $5 }'   

wget ifmo.ru
mv index.html Test10.html

ssh localhost
mkdir hi
exit

scp localhost:~/.bash_history /tmp
rsync ~/.bashrc /tmp
diff ~/.bashrc /tmp/.bashrc 
```