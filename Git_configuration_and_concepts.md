# Git configuration and some concepts

In this little summary you will find some of the most fundamental commands for git and git hub.

### Initial configuration
git config --global user.email/name " ": With this command you can start configuring git by adding your email or username you want to register. (Use the same email and name as your git hub account)   

### Starting a project from zero or cloning an existing repository
Follow the next steps...
git init | for initializing git
If you want to... :
git clone *repository URL* | for cloning an specific repository from git
or
git remote add *name* *URL* | for connecting to an existing repository

### Basic workflow command to stage and commit
git pull *origin main* | This command is for extracting the code of the repository. 
git status | This command is for checking which changes are staged or not
git add *name* | With this command you add the changes you made to the staging area. 
git commit -m "*any message*" | With this command you save the changes in git's memory.
and then...

### Push to a remote repository 
push git  *origin main* | With this command you push your information to a git hub repository.

### Branches
git branch *name* | With this command you create a branch where you can work in parallel.
git checkout *name*| Change branch
or
git checkout -b | Create and change to another branch

git merge *name* | Fusion branches and make a commit 
git branch -d *name* | Delete the branch
git branch --contains *commit* | This command is for seeing in which commit that branch stayed.

### Git flow
git flow is a sort of library that includes abbreviated commands for facilitating the usage of git and git hub by adding pre-made branches and other tools.
It initialize with:
``git flow init`` 

Then accept or change which is going to be your default branch and your development branch. 
Then the same with all the configuration of supporting branches.

If you want to invoke them just use the following command:
``git flow *name of pre-made branch* start *name*`` | 
and for deleting it
``git flow *name of pre-made branch* finish *name*``
As you can see its a different way of writing git commands by using just one line