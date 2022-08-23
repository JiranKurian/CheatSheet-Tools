# GIT COMMANDS CHEAT SHEET

This is a simple cheat sheat which contains the basic commands and its details which is required to play with git.
***

## Getting Started

|Name               |Syntax           |Description                        |
|------------------ |---------------- |---------------------------------- |
|git config|<br>`git config –global user.name “[name]”`<br><br>`git config –global user.email “[email address]” `<br><br>|This command sets the author name and email address respectively to be used with your commits.|
|git init|<br>`git init`<br><br>`git init [/path/repositoryName]`<br><br>|This command create or start a new local repository.|
|git add|<br>`git add [file]`<br><br>`git add *`<br><br>|These command adds a file to the staging area or add all files to the staging area.|
|git rm|<br>`git rm [file]`<br><br>|This command deletes the file from your working directory and stages the deletion.|
|git commit|<br>`git commit -m "[Commit message]"`<br><br>`git commit -a`<br><br>|This command records or snapshots the file permanently in the version history. The second command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.|
|git status|<br>`git status`<br><br>|This command will list which files are staged, unstaged, and untracked.|
|git log|<br>`git log`<br><br>`git log --summary`<br><br>`git log --oneline`<br><br>|This command will display the entire commit history.|

   
## Branching and Merging
|Name               |Syntax           |Description                        |
|------------------ |---------------- |---------------------------------- |
|git branch|<br>`git branch`<br><br>`git branch -a`<br><br>|These commands will list the current branch or list all the branches|
|git branch|<br>`git branch [branch name]`<br><br>|This command will create a new branch with the given name|
|git branch|<br>`git branch -d [branch name]`<br><br>|This command will delete the given branch|
|git branch|<br>`git push origin --delete [branch name]`<br><br>|This command will delete the given branch from remote|
|git checkout|<br>`git checkout [branch name]`<br><br>|This command will switch to the given branch|
|git merge|<br>`git merge [branch name]`<br><br>|This command will merge the given branch into the active branch|
|git merge|<br>`git merge [source branch] [target branch]`<br><br>|This command will merge the sourec branch into the target branch|

      
## Remote Repository

|Name               |Syntax           |Description                        |
|------------------ |---------------- |---------------------------------- |
|git clone|<br>`git clone [url]`<br><br>|This command is used to obtain a repository from an existing URL and create a working copy of a local repository.|
|git remote add|<br>`git remote add [url]`<br><br>|This command creates a new connection to a remote repo.|
|git fetch|<br>`git fetch`<br><br>|This command will fetch from the remote repo.|
|git pull|<br>`git pull`<br><br>|This command will fetch the content form remote repository and immediately merge it into the local repository|
|git push|<br>`git push`<br><br>|This command will push the branch to remote repository, along with necessary commits and objects. Creates named branch in the remote repo if it doesn’t exist.|
