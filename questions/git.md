# Git

**Q1** How do access a file in VSCode, directly from Git?

> First, you access the file you need in git. Once your file is opened, you type: "code ." on your command line, then hit enter. This command will open your current file in VSCode. 

--- 

**Q2** How do you save changes you have made to a repository file that you have cloned from GitHub, in Git?

>Step 1

>Type the command line: 
```
git add index.js
```

>Step 2

>Type the in command line: 
```
git commit -m “Name your changes.”
```

>Step 3

>Type the in command line:
```
git push -u origin main
```

--- 

**Q3** How do you access the history of your 10 last commands in git?

>You can type in the command line: 
```
history | tail -n 50 >> history.md
```


--- 