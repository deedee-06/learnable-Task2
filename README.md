# learnable-Task2

**Version Control** is a system that records or saves changes made to a file or set of files while it is beng worked on. It allows a developer or anyone working on the file to easily undo changes, compare codes, track where an error or bug might be coming from, and keep track of peoples work ( that's if it involves a group of people).

**Difference between Git and Github**
Git is a version control system that allows sevelopers track changes in their code. It can run or function without Github. It is installed locally on the computer. Files stored on git cannot be retrieved if system is stolen or damaged.

Github is a web-based service for hosting Git repositories. Unlike Git, Github cannot function without Git. It provides a web interface to view file changes. It is easy to retrieve files if system is stolen.

**3 Other Github Alternatives are;**
a. Gitea
b. Bitbucket
c. Google Cloud Source Repositories

**Difference Between Git Fetch and Git Pull**

*Git Fetch:* is used to fetch all changes from the remote repository to the local repository without merging
into the current working directory. There is no possibility of merge conflicts.

*Git Pull:*  This is a combination of git fetch and git merge. It brings the copy of all the changes of a remote
repository and merges them into the current working directory. Merge conflict is possible if the remote and the 
local repositories have done changes at the same place.


**Git rebase** is a command that integrates changes made from one branch to another branch. That is, it takes uo all the 
changes that were committed on one branch and replayed on a different branch.
The command for git rebase is; *git rebase branchname*

**Git Cherry-pick** is a command that allows one choose any specific Git commits from a branch and adding it to 
another branch. It is usually used when the developer doesn't want to merge the whole branch, and needs some of the commit.
The command for cherry-pick is; *git cherry-pick <commit-hash>*