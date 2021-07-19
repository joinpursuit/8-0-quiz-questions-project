#Github
**Q:** What do you need to do before cloning a repository into your laptop? And why?
> You have to go to a directory/folder that is not a git repository. Then go to a directory that will be a parent directory to the respository that you're cloning. When in that parent directory, there shouldn't be another folder with the same name as the repository you're cloning. 
    1. You want to make sure thatit isn't a git directory you're cloning into because it can be confusing to users of the repositories which is the project that youre working on/editing.
    2. If there is another folder that has the same name, the git clone command will not run if th another folder has the same name and has files in it. If there another folder with the same name and is empty, git clone will fill it.

**Q:**  What is a branch in GitHub and why is it beneficial? How is a branch created and accessed via the terminal?

> A branch is an isolated enviroment to test new new/different code without affecting the master branch
If satisfied with the new code, the user can them commit the changes and merge the changes to the master branch.
Branches allows multiple members to work on different parts of the project at the same time without afftecting the main branch. With this in place, this allows visibility as to which team members made their respective changes to a project.
```
Git branch <branchname>
To work within the branch then type git checkout <brandhname>
```
Or
```
git checkout -b <branchname>
```

**Q:**  How can a user contribute changes to a repository on GitHub?

> If you have read permissions to a repository, then you can create a pull request. If you want to create a branch of repository, you need to have write permissions. If you don't have write permissions, you have to fork the repository forst. After executing the changes, you can create a pull request on the forked repository.

