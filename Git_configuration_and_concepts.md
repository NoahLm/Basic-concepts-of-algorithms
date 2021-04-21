# Git configuration and some concepts

In this little summary you will find some of the most fundamental commands for git and git hub.

### Initial configuration
git config --global user.email/name " ": With this command you can start configuring git by adding your email or username you want to register. (Use the same email and name as your git hub account)   

### Starting a project from zero or cloning an existing repository
Follow the next steps...
git init | for initializing git
git clone *repository URL* | for cloning an specific repository from git

### Basic workflow command to stage and commit
git add *name* | With this command you add the changes you made to the staging area. 
git commit -m "*any message*" | With this command you save the changes in git's memory.

### Push to a remote repository 
push git  *origin main* | With this command you push your information to a git hub repository.

### Branches
git branch *name* | With this command you create a branch where you can work in parallel.
git checkout *name*| Change branch
git merge *name* | Fusion branches and make a commit 
git branch -d *name* | Delete the branch

### Git flow
git flow is a sort of library that includes abbreviated commands for facilitating the usage of git.
