Задание
```
Lab 15 (till 25 december)

1. Write a script 'Lab15-1' that creates tar-archive of some directory
   content (without directory name), the archived directory should
   specified as second argument of scripts, while file name of
   the archive should specified as first one. The script should verbosely
   list processed files. The archive should be gzipped.
   Run your script to archive the directory Test15 with name Test15.tgz
2. Write a script 'Lab15-2' that extracts from tar-archive specified
   as first argument to directory specified as second argument.
   The script should verbosely list processed files.
   If there are argument else these are the names of files to extract.
   Run your script to extract files t1.png and t3.png from Test15.tgz to /tmp.
3. List al packages that's installed on your system with names begining
   letter 'b' and save this list in 'bpkgs.lst' file.
4. Install package'unrar'(as superuser).
   Demonstrate it's installed: 'rpm -q unrar'
```
Порядок выполнения команд:

```
./Lab15-1 Test15.tgz Test15
./Lab15-2 Test15.tgz /tmp t1.png t3.png
rpm -qa | grep "^b"
rpm -qa | grep "^b" > bpkgs.list
sudo yum install unrar
rpm -q unrar
```
