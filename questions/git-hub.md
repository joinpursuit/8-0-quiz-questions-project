What is the difference betwen git and GitHub?
Git is a version control system that allows you oversee and keep track of your source code history. GitHub is a cloud-based hosting service that allows you manage Git repositories.

How do you create a new repository on GitHub from your local computer?
In order to create a new repository on GitHub you need to:
Go to your Terminal, change the current working directory to your local project.

Initialize the local directory as a Git repository.
using: git init

Add the files in your new local repository. This stages them for the first commit.

using :git add .

or:

git add --all

Commit the files that you've staged in your local repository.
using: git commit -m 'First commit'

Copy remote repository URL from your GitHub repository.

In Terminal, add the URL for the remote repository where your local repostory will be pushed.

using: git remote add origin <remote repository URL>
Sets the new remote:

using: git remote -v

Push the changes in your local repository to GitHub.

git push origin master
//or origin main depending on preference
Pushes the changes in your local repository up to the remote repository you specified as the origin

What is forking and what is cloning? Why are these useful?
Forking a repository is when you create a duplicate of it to your own GitHub account. The "forked" repository is connected to the original repository. To Fork a repository, you can click the Fork button at the top of any repository you have access to. You will be brought to a new page which is your version of the forked repository-- this page should have your account name in the URL. Cloning is the process of taking a remote repository from GitHub and creating a synchronized version of it on your computer.

Before cloning, you should do the following on your local machine:

Navigate to a directory that is the parent directory of where you want this repository to live.

Make sure that there is no folder inside the directory with the same name as the repository you are cloning.

Once you've confirmed the above, you will click on the green "Code" button and then copy the URL that is there.

On the command line, you will then run the following command, replacing <url> with the URL you just copied.

git clone <url>

This will start a process of downloading all of the files associated with your forked repository. All of those files will go into a new folder with the same name as the repository.





