# Git

**Question #1**
```
Which flag would be used to automatically stage all modified files when committing new files?
```
**Answer**
```
The -a option will allow all unstaged modified files to be committed. Keep in mind that only the files that the Git repository recognize will be committed and all new files must be added before committing.
```
**Question #2**
```
After creating a new directory,  What is the next command we would run in our CLI in order to start a new Git repository?
```
**Answer**
```
$ git init would be the correct command for initializing a new repisitory in our command line. Most commands wont be available outside of an initialized repo and for that reason $ init will be one of the first commands we will run when starting a new project. Unless we use $ Git clone which automatically creates a new repository for us when we clone to our machines.
```
**Question #3**
```
fatal: Not a git repository: <absolute path to .git/modules/*>

Why does this error occur?
```
**Answer**
```
The error is caused by accessing a directory using an absolute path to files stored in various locations on your machine.
```
