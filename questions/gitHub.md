# GitHub

**Q-1:** What is `GitHub`?

> A-1: `GitHub` is a `Git` r_epository hosting service_. Git is a command line tool, while GitHub provides a web-based graphical interface. It has many features such as Collaborative Coding, Automation & CI/CD, Security, Client Apps, Project Management, Team Administration, and Community.
---

**Q-2:** Why should I use the terminal if I can see things on `GitHub` and create/edit repositories in the browser?

> A-2: `GitHub` is a _GUI_, not a _CLI_. This means that by using the terminal, you are more effectively managing your code. It is being done locally on your own computer, rather than on a server/browser. You can also fork other people's projects, clone them locally to your own computer, and work offline. You can do some Git commands on your computer before you decide to `push` your code to `Github`. You can start on GitHub creating a repository, then clone it onto your own computer to work on it locally. Once you've done that, you can do some of these git commands:

* `git init` - initalizes the git repository (and it creates a hidden file called `.git` within your project's directory)
* `git add` - add file(s) to the staging area
* `git commit` - from the staging area, create a commit message
* `git push` - this will be done when you are connected to the internet, to push your code over to GitHub.
* `git status` - tells you the current status of your files in your git repository.
* `git diff` - shows you the changes between commits

Additional commands that may be helpful:
* `git rm --cached` - to un-stage a file
* `git restore` - this restores from the last time you staged a file.

---

**Q-3:** How do you make a `pull request` on GitHub?

> A-3: After you have added all your files using the CLI/terminal, added your commit messages, you'll want to do a `git push` command. Once you've pushed the code to GitHub, you can go to GitHub in the browser to where you cloned your file from. Make sure you are on the correct _branch_ if you have multiple ones, and then click on the `Contribute` button. Then you should see a green `Open pull request` button, and click on that. From there, you will see a green checkmark and `Able to merge.` Then add a relevant title and description, and you can click the green button `Create pull request`. Then, you should see your pull request. Depending on who the owner of the repository is, you may have to wait for the owner to review the changes before the request is accepted or not.


<!-- Resources:
What is GitHub:
https://techcrunch.com/2012/07/14/what-exactly-is-github-anyway/?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAALXQDHXORAZSgytqTR00yzLSKhEk1oKjX8gdrWbYkyqIZYJSUMpBeiy4_sGq8cB5pOM101yUF_Y5KpJv2_8vFpOH3OHjmK7QyxfVB9kR2zsnVN0aQB-Hf465qOu8JML95uSwP8DH7EqKtCd-3Tr6AeIYjg8nxfpRZrEQrfZkKhlh 

GitHub Features:
https://github.com/features

Git Diff:
https://www.google.com/search?q=git+diff+meaning&oq=git+diff+meaning&aqs=chrome..69i57j0i22i30l7j0i390j69i64.4030j0j7&sourceid=chrome&ie=UTF-8
-->