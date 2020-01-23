# RHCSA-Practise
#to create a blank file
touch redhat
#to create text file
touch redhat.txt
#to create multiple files
touch redhat{1..5}
#to display the list of files and folder
ls
long lasting format
ls -l
to display all files including hidden files
ls -a
#to create a directory
mkdir redhat
mkdir redhat1 redhat2 redhat3
#to create collabrative or parent directory
mkdir -p abc/red/hat
#to create directory with space
mkdir 'red hat'
#displays the full path name of the current location
pwd (Present Working Directory)
#to change directories
cd
cd - (changes directory to the directory where user was previously working)
cd .. (move up to the parent of the current location)
cd bin (move to the binary location,from the root directory)
cd .. (move up two levels from the current location)
#to copy one or more files 
cp file1 file2
#to copy directories with contents,we requires the recursive option
cp -r abc1 abc2
#to move files and renames files
mv file1 file4 (renaming of file1)
mv file1 file2 (moving of file1)
#to remove files or directories
rm file (it deletes files )
rm -r redhat (to delete directories,we use -r option)
