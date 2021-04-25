
# Welcome to basic command of git and bash!
In this little summary you will find some of the most fundamental commands for manipulating your computer.

### Create and delete directories
```mkdir *name*``` : With this command you can create new folders instantaneously.
```rmdir *name*``` : With this command you can delete a folder. However, it needs to be empty to be deleted.
 
### Switch to another folder

```pwd``` | For checking your present position
```cd *name*``` | For changing to an specific folder.
```cd ~/*name*``` | With this command you can move trough your computer folders. Just that it considers your home location.
```cd /*name*/*name*...``` | For changing to an specific folder writing all its direction.   

### Compare
```git diff *branch1 branch2*``` | For checking differences between two branches.
```git diff *file 1 file 2*``` | This command is for checking the difference between two files.
```git diff --cached``` | For checking the difference with the last commit.
```git difftool``` | For accessing the differences visually with an external window.
 

### Find files, folders and inside files
-For a general view:
```ls``` | This command shows you the files and folders of your present direction.
```ls -a``` | Same as the last one but it also shows you hidden folders.

-For specific things:
| Command | Useness |
| ------ | ------ |
```find``` | This command is for finding specific files. 
After the "find" if you write a "." is inside your present folder, a "/" for your whole system and a "~" for you home folder.
```find . *name*``` | For searching files with the name you wrote.
```find . -name *.format*``` | For searching files with an specific extension.
```find . -not *name*``` | For searching files without an specific word. 

### Create and edit text files
| Command | Useness |
| ------ | ------ |
```touch *name*``` | This command just creates any kind of file you tell the computer to do.
```nano *name*``` | This command opens nano's text editor, where you can create or edit any kind of plain text file.
```vim *name*``` | Similar as nano, but another editor.
```code *name*```| Similar with vim and nano, But if you have Visual Studio Code, it opens a window of it with the file you want to create or modify.

### Get the state of the computer:
Computer hardware:
| Command | Useness |
| ------ | ------ |
```echo``` | You can configure some scripts using this command for checking the state of your computer's hardware and show it in the terminal using the previous command. |

Git changes:
| Command | Useness |
| ------ | ------ |
| ```git status``` | Inside the folder this command tells you if there is any kind of change inside the files. |