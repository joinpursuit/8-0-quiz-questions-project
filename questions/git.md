# Git

**Q:** What does the flag `-m` stand for when using `git commit -m`?

> **Answer**:

> The flag `-m` is short for `--message` option. This is added to the git commit command to allow a message for the commit. It should describe what the commit is or what it has changed.

---

**Q:** What are commonly used commands in Git that are  used to interact with GitHub?

> **Answer**:

> * `git clone <GitHub repository url>` is a commonly used command to get a copy of an existing Git repository that is hosted on GitHub. 

> * `git push` is another commonly used command that allows you to send (or push) the commits from your local branch in your local Git repository to the remote repository on GitHub. 

---

**Q:** What does the following Git command(s) do?

```
git init
git log
```

> **Answer**:

>`git init` will initialize a hidden Git-specific directory named `.git` inside the current working directory.

> `git log` will show the git commit history for project.

---

**Q:** What command outputs the following?

```
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)
```
> **Answer**:

> `git status`

> This command checks the status of the git repository. It will show anything untracked, tracked, and items staged and ready to be committed.

---