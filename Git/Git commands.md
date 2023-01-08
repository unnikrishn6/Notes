## GIT:

### What is Git?

GIT is a version control system.
* Saves history of changes
* Revert to prior versions
* Merge work from multiple collaborators

### Repository: 
    A repository is a directory (aka folder) where you are saving all the code files for any given project.  
    First, you make a folder and then use git init to make it into a git repository.
    
### Branching
    "On branch master" (means on the main project, not a side branch)
    to add to main branch use -m
    to add to side branch use -t

### git config
    This command configures the user. 
    The Git config command is the first and necessary command used on the Git command line. 
    This command sets the author name and email address to be used with your commits.
    Syntax
    $ git config --global user.name "abcd"  
    $ git config --global user.email "abcd@gmail.com"  

### git init
    This command is used to create a local repository.
    Syntax
    $ git init Demo  

### git clone
    This command is used to make a copy of a repository from an existing URL. 
    Syntax	
    $ git clone https://www.github.com/[USERNAME]/...git

### git add
    This command is used to add one or more files to staging (Index) area.
    Syntax
    To add one file (tab to select file)
    $ git add <Filename>  

    To add all files
    $ git add .

### git commit -m
    This command changes the head. It records or snapshots the file permanently in the version history with a message.
    Syntax
    $ git commit -m "Commit Message"  

### git commit -a
    If you want to commit any files you have added with git add, and also commit any files you have changed since then.
    This is used when After add command, if a file which is modified needs to be added.
    Syntax
    $ git commit -a -m "2nd commit"

### git status
    The status command is used to display the state of the working directory and the staging area.
    Shows you whats staged but not yet committed, and tells you if any files have changed since last commit
    Syntax
    $ git status

### git push 
    It is used to upload local repository content to a remote repository. 
    Pushing is an act of transfer commits from your local repository to a remote repo.
    To send your changes to the master branch of your remote repository.
    Syntax
    $ git push origin master

#### git log   (shows history of changes made)
#### git add -u   (tells commit to remove files you've deleted)
#### git push origin master   (sends updates to github)
#### git pull origin master   (pulls updates from github)

# Git commands to type in terminal:

In terminal, navigate to the folder you want to use
* git init   (initializes repository; "." tells git to look for files in this folder)
* git add .   (stages files for a commit; the dot adds all files in the directory) 
* git commit -m "message" 
    * the -m commits to the master branch
* git status   
* git commit -am "message"
* Link github repository to your computer's local repository: 
    * git remote add origin  "github.com/[USERNAME]/[REPO_NAME].git"
    * git push -u origin master
* git add -u   (tells commit to remove files you've deleted)
* git push origin master   
* git pull origin master   
</pre>
