#  GIT COMMANDS 

## git config
_This command sets the author name and email address respectively to be used with your commits._
- Usage: git config –global user.name “[name]” 
- Usage: git config –global user.email “[email address]” 

## git init
_This command is used to start a new repository._
- Usage: git init [repository name]

## git clone
_This command is used to obtain a repository from an existing URL._
- Usage: git clone [url]

## git add
_This command adds a file to the staging area._
- Usage: git add [file]

_This command adds one or more to the staging area._
- Usage: git add *

## git commit
_This command records or snapshots the file permanently in the version history._
- Usage: git commit -m “[ Type in the commit message]” 

_This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then._
- Usage: git commit -a 

## git diff
_This command shows the file differences which are not yet staged._
- Usage: git diff 

_This command shows the differences between the files in the staging area and the latest version present._
- Usage: git diff –staged 

_This command shows the differences between the two branches mentioned._
- Usage: git diff [first branch] [second branch] 

## git reset
_This command unstages the file, but it preserves the file contents._
- Usage: git reset [file] 

_This command undoes all the commits after the specified commit and preserves the changes locally._
- Usage: git reset [commit] 

_This command discards all history and goes back to the specified commit._
- git reset –hard [commit]

## git status
_This command lists all the files that have to be committed._
- Usage: git status

## git rm
_This command deletes the file from your working directory and stages the deletion._
- Usage: git rm [file]

## git log
_This command is used to list the version history for the current branch._
- Usage: git log

_This command lists version history for a file, including the renaming of files also._
- Usage: git log –follow[file]

## git show
_This command shows the metadata and content changes of the specified commit._
- Usage: git show [commit]

## git tag
_This command is used to give tags to the specified commit._
- Usage: git tag [commitID]

## git branch
_This command lists all the local branches in the current repository._
- Usage: git branch

_This command creates a new branch._
- Usage: git branch [branch name]

_This command deletes the feature branch._
- Usage: git branch -d [branch name]

## git checkout
_This command is used to switch from one branch to another._
- Usage: git checkout [branch name]

_This command creates a new branch and also switches to it._
- Usage: git checkout -b [branch name]

## git merge
_This command merges the specified branch’s history into the current branch._
- Usage: git merge [branch name]

## git remote
_This command is used to connect your local repository to the remote server._
- Usage: git remote add [variable name] [Remote Server Link]

## git push
_This command sends the committed changes of master branch to your remote repository._
- Usage: git push [variable name] master

_This command sends the branch commits to your remote repository._
- Usage: git push [variable name] [branch]

_This command pushes all branches to your remote repository._
- Usage: git push –all [variable name]

_This command deletes a branch on your remote repository._
- Usage: git push [variable name] :[branch name]

## git pull
_This command fetches and merges changes on the remote server to your working directory._
- Usage: git pull [Repository Link]

## git stash
_This command temporarily stores all the modified tracked files._
- Usage: git stash save

_This command restores the most recently stashed files._
- Usage: git stash pop 

_This command lists all stashed changesets._
- Usage: git stash list

_This command discards the most recently stashed changeset._
- Usage: git stash drop

