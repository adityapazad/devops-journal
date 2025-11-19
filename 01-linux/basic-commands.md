# COMMANDS

## BASIC
- `pwd` - current location
- `whoami` - current user
- `date` - display date
- `ls (-lt | -la)` - display files and directories in current location, (more info | hidden files)
- `clear` - clears terminal

## CREATING, DELETING, UPDATING
- `cat <file>` - display content of file 
- `less <file>` - read a file and searches for a word
- `more <file>` - view content of file page by page
- `touch <file>` - create a file
- `rm <file>` - delete a file
- `vi <file>` `nano <file>` - edit a file
- `mkdir <file>` - create a directory
- `rmdir <file>` `rm -rf <file>` - delete a directory 
- `cd ..` `cd /path/folder` - move to another directory
- `cp <file> /destination/path` - copy paste a file
- `cp <fileA> <newFile>` - copy content from a file to another
- `mv <file> /dest/path` - move file from a folder to another
- `mv <fileA> <fileNewName>` - renames file
- `head -5 <file>` - display top 5 lines from a file
- `tail -5 <file>` - display bottom 5 lines from a file
- `sort <file>` `sort -r <file>` - sort content of a file , sort in reverse
- `sort <file> | uniq` - removes duplicate from a file
- `split -l 3 <file>` - a file has 9 line. it splits that file in 3 different files
- `grep "word" <file>` - display lines that consists the word
- `egrep "word1 | word2" <file>` - display lines that consists the 'words'
- `* [] {}` - WILDCARDS
- `shuf <file>` - shuffle content of the file
- `wc -l <file>` - counts number of lines in a file
- `cmp <fileA> <fileB>` - compare if files are identical or not
- `diff -u <fileA> <fileB>` - compare and display difference between two files
- `find /path/ -name <file>` - find a file
- `updatedb` -> `locate <file>` - better way to find a file
