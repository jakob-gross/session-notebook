git switch -c <branchname> create a new branch and switch to it
git switch <branchname> switch branches
git branch list your branches
git branch -a list all branches (local and remote)
git branch -d <branchname> delete a branch

Branches
Branches are an important part of working with Git. Any commits you make will be made on the branch you’re currently “checked out” to. Use git status to see which branch that is.

$ git branch [branch-name]

Creates a new branch

$ git switch -c [branch-name]

Switches to the specified branch and updates the working directory

$ git merge [branch]

Combines the specified branch’s history into the current branch. This is usually done in pull requests, but is an important Git operation.

$ git branch -d [branch-name]

Deletes the specified branch
