Задание
```
Lab 08 (till 27 november)
1. List the contents of direcitory Test08
2. Copy the file "2Edit" to file "Edit.Ok"
3. Replace in file "Edit.Ok" all misspelled words with the correct ones"
4. Compare files "2Edit" and "Edit.Ok" using 'diff' utility (without options)
5. What is the size of file "Edit.Ok"
```
Порядок выполнения команд:
```
ls Test08
cd Test08
cat 2Edit > Edit.Ok
nano Edit.Ok 2 
//заменить слова с ошибками
diff 2Edit Edit.Ok  
wc -c Edit.Ok
```