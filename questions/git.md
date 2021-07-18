# Git Quiz

**Q1:** Please create a directory called 'Folder' and add a blank markdown file titled 'readme' and finally initialize a git reporitory in the directory.

```zsh
mkdir Folder
touch ./Folder/readme.md
cd ./Folder
git init
```

---

**Q2:** What is the git command to check the status of a repoistory?

> We can check the status of our Git repo by typing git status. This will tell us which files, if any, have changed since we last updated our repo.
```zsh
git status
```

---

**Q3:** Consider being within a git repo, how would you go about staging and commiting all updates/changes to the repository?
 
 > git add adds your modified files to the queue to be committed later. Files are not committed. git commit commits the files that have been added and creates a new revision with a log

 ```zsh
 git add .
 git commit -m"Meaningful message detailing the overall changes made"
 ```

---