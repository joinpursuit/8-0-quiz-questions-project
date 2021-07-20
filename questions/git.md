# Git

## Question # 1: 
What kind of tool is Git?

### Answer:
- Git is a Version Control Sofware. There are other names for Version Control Software which is commonly referred to as SCM or RCS. SCM is known as Source Code Management. RCS is known as Revision Control System. 
- It is a way for you to keep track of changes in your code if something goes wrong, you can compare different code versions and revert back to those previous version. Multiple developers can work on the same code and change or update the code at the same time.

---------------
## Question # 2: 
What is the advantage of using Git?

### Answer: 
- Git is free and open sourced meaning it can be redistributed and modified. 
- It supports non-linear development meaning users from all over the work can work on the project remotely. A user can select any part of the project and update it. 
- It offers branching. That means users can make changes in the project withouth affecting the original version. The master branch will always have a production quality of code. If there are new features, you can work on the branch and then merge it to the master branch. 
- It is cross-platform meaning it has multiple sets of technologies, languages, and frameworks. It supports almost all operating systems.
- It is still available when you are offline.
- Uses multiple repositories. There is a central repository meaning it has only one remote repository. There are also a series of local repositories. Local repository typically means you can make changes in your computer.
- There are no single point of failure. This means if the central repository goes down or a code break the whole build, no one can commit their code until the repository is fixed. However, in Git, each developer has their commited code local in their computer. They can continue to commit until the central repository is fixed, then they can push their changes.

---------------
## Question # 3: 
Is there any disadvantage in using Git?

### Answer: 
- Yes, there can be a complex and bigger history logs which will become increasingly difficult to understand as the projects get larger. 

---------------
## Question # 4:
Is Git the only Version Control Software Tool? If not, please name some examples of VCS tool.

### Answer:
- CVS (Concurrent Versions System)
- SVN (Apache Subversion)
- Mercurial
- Monotone
- Bazaar
- TFS (Team Foundation Server)
- VSTS (Visual Studio Team Services)
- Perforce Helix Core
- IBM Rational ClearCase
- Revision Control System
- VSS (Visual SourceSafe)
- CA Harvest Software Change Manager
- PVCS (Polytron Version Control System)
- darcs (Darcs Advanced Revision Control System)

---------------
## Question # 5:
Name some common git commands used and explain what they do.

### Answer:
**git status**: Displays the state of the working directory and checks for any changes that have been staged.

**git clone**: It is used to download the project in your local machine.

**git init**: This command is used when you want to start a new empty repository. It will create a ".git" directory.

**git commit**: After changes are done on locally on your computer, you can save them by committing to them. It is a saving point.

**git push**: It will push the locally committed changes to the branch you are using. If the branch is remotely tracked, you can just type in "git push" with no parameters. If the branch has not been tracked, you will need to run the command:
```
git push --set-upstream <remote branch> <branch name>
```
**git diff**: Use this command to see unstaged changes, staged changes, or comparing two branches.

**git add**: Use this command if you need to stage changed files. You can individually write the file name or to add all files, you just need to type "git add ."

**git branch**: This will list all the branches in your repository. You can create a new branch or delete a branch by typing:
```
git branch -d <branch name>
```
