### pwd: shows the current path in a hierarchical directory 

### cd: change directory

### ls: list files and directories
#### More on ls

```sh
ls /bin List diles in the /bin directory (or any other directory we care to sperify)
ls -l List the files in the working directory in long format
ls -l /etc/bin List the files in the /bin directory and the /etc directory in long format
ls -la .. List all files
```
### Shell command: clear
### cp: copy files and directories
#### More on  cp
```sh
cp file1 file2 copies the contents of file1 into file2. If file2 does not exist, it is created; otherwise, file2 is silently overwritten with the contents of file1.
cp -i file1 file2 Like above however,since the "-i"(interactive) option is sepcified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.
cp file1 dir1 Copy the contents of file1 (into a file names file1)inside of directory dir1
cp -R dir1 dir2 Copy the contents of the directory dir1. If directory dir2 does not exist, it is created. Otherwise, it creates a directory names dir1 within directory dir2.
```
### mv: move files and directories or rename them
```sh
mv file1 file2 If file2 does not exist, then file1 is renamed file2. If file2 exists, its contents are silently replaced with the contents of file1.
mv -i file1 file2 Like above however, since the "-i"(interactive)option is sepcified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.
mv file1 file2 dir1 The files file1 and file2 are moved to directory dir1. If dir1 does not exists, mv will exit with an error.
mv dir1 dir2 If dir2 does not exist, then dir1 is renames dir2. If dir2 exists, the directory dir1 is moved within directory dir2.
```
rm: delete files and directories
```sh
rm file1 file2 Delete file1 and file2.
rm -i file1 file2 Like above however, since the "-i"(interactive) option is specified, the user is prompted before each file is deleted.
rm -r dir1 dir2 Directories dir1 and dir2 are deleted along with all of their contents.
```
### mkdir: make a new directory
### Manipulation: Wildcards
### Help command: help,men
### exit
