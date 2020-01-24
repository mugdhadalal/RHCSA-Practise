###### RHCSA-Practise
> Basic Commands
* **to create a blank file**
```touch redhat```
* **to create text file**
```touch redhat.txt```
* **to create multiple files**
```touch redhat{1..5}```
* **to display the list of files and folder**
```ls [long lasting format]```
```ls -l```
* **to display all files including hidden files**
```ls -a```
* **to create a directory**
```mkdir redhat```
```mkdir redhat1 redhat2 redhat3```
* **to create collabrative or parent directory**
```mkdir -p abc/red/hat```
* **to create directory with space**
```mkdir 'red hat'```
* **displays the full path name of the current location**
```pwd[Present Working Directory]```
* **to change directories**
- ```cd  (changes directory to the directory where user was previously working)```
- ```cd .. (move up to the parent of the current location)```
- ```cd bin (move to the binary location,from the root directory)```
- ```cd ..(move up two levels from the current location)```
* **to copy one or more files** 
```cp file1 file2```
* **to copy directories with contents,we requires the recursive option**
```cp -r abc1 abc2```
* **to move files and renames files**
- ```mv file1 file4 (renaming of file1)```
- ```mv file1 file2 (moving of file1)```

> Editing files with VIM
* **open file with** 
```vim filename```
1. *press **I** to enter insert mode*
2. *press **ESC** to return to command mode*
3. *enter **w** to save the file*
4. *enter **wq** to save the file and quit Vim*
5. *enter **q!** to quit vim and to discard changes made in the file*
6. ***p** to paste,
  - **dd** to delete single line
  - **ndd** to delete multiple lines
  - **y** to copy paragraph,**O** to insert new line,**/word** to search a word,**%s/word/word2** to replace a word with word2 and %S/word1.word2/g to replace all words 
To create file and to save data in that file we use cat,cat >filename to store a data,cat >>filenamr to add more data,cat filename to view the data in the file
Head is used to show the upper lines and tail is used to show below lines ex head –n 30 filename
