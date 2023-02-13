# Useful-Git-Linux-Commands

Following are few of the useful git and linux commands that are very helpful. 

## Useful Git Commands

1. git init

Command:
```
$git init
```
Description: 

- It is used to create a new git repository. 
- When we run this command in any given directory it will create a new git repository of that directory. 
- A '.git' hidden directory is created after running git init. Which is the git directory created. 

2. git branch

Command:
```
$git branch [name-of branch]
```
Description: 

- This creates a new branch locally.
- You have to give the name for the branch that you want to create after git branch.


3. git commit

Command:
```
$git commit -am "[commit-message]"
```
Description: 

- It saves the changes locally. 
- All the new files created or the ones that are changed are saved.
- You have to provide a message also know as the commit message which acts as a label for the changes.
- Commit helps in readability for other developers. 

4. git clean

Command:
```
$git clean -n
```
Description: 

- It deletes untracked files from the working directory in the repository.
- It will first do a dry run and tell you which files would be removed.
- These files are the ones which are present in the directory of the repository but are not added to the repositories index.
  

5. git clone

Command:
```
$git clone [url-of-repository]
```
Description: 

- It creates a copy of the remote repository locally.
- Code from that url will be downloaded automatically once this command runs.

## Useful Linux Commands

1. ls

Command:
```
$ls
```
Description:

- This lists the contents of the directory. 
- Content such as files and other directories are listed.

2. pwd

Command:
```
$pwd
```
Description:

- This prints path of the current working directory you are in.
- It gives the whole absolute path of the directory.

3. cd

Command:
```
$cd [name-of-directory-you-want-to-move-to]
```
Description:

- It changes the current directory to the one you provided after cd.

4. mv

Command:
```
$mv [source-file] [destination-path]
```
Description:

- It is used to move the files and directories from one path to another.
- First we give the file/directory name we want to move.
- Then we give the path where we want to move it to.

5. exit 

Command:
```
$exit 
```
Description:

- Closes the terminal.
