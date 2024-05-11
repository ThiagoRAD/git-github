## Just some notes from
- https://www.codedex.io/git-github
-Overall not really good content for newcomers sadly.


### Check if Git is installed

run ``git --version`` on the terminal, you should see a version number like ```git version z.y.z``

### Git Init

The ``git init`` command initializes a new Git repo (local repo)

### Git Remote

The command to add a connection to a remote repository is ``git remote add origin <repository_url>``

### Git Add

The ``git add`` command tells Git which changes you want to include in the next commit.

### Git Commit 

To commit the staged files added with the Git Add command we use ``git commit -m 'Your commit message here!'``

### Git Status

The ``git status`` command is used to check the status of your files.
- Staged files are ready to be commited
- Unstaged files are not yet ready to be committed.
- Untracked files are new files that Git has not seen before.

### Git Push

- Usually the first time you push to a branch we do the following ``git push -u origin main``
- Once that's set, any commits you push to this branch will just require ```git push``

### Cloning

``git clone https://github.com/YOUR_USERNAME/EXAMPLE_REPO.git``

### Branching

- Creating a new branch ``git branch new-branch-name``
- Switching to the branch ``git switch new-branch-name``
- Create and switch at the same time ``git checkout -b <new-branch-name>``
