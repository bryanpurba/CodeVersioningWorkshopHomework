# CodeVersioningWorkshopHomework

## git general
- git is tool that is primarily used for version control
- to initialize a git repo, you can use command `git init`
- use command `git add` to stage changes and 
- use command `git commit` to commit the staged changes
- git commit purpose is to saved a snapshot of the project 
- you can use `git status` to findout
	- current working branch 
	- unstaged changes 
- you can use `git log` to findout the historical of saved snapshot of project
- if you do a mistake, and need it to undo a commit, you can use command `git reset <commit-id>` you can change `<commit-id>` to HEAD~1 to change it into previous commit

## Github
- Github is a remote repository Hosting that can host git repositories 
- To copy remote repository to local repository, you can use `git clone`
- `git fetch` is a command to fetch changes from remote repository and to apply the changes into local repository you can use `git merge`
- alternatively, you can use git pull to fetch the changes from remote repository and apply the changes 
- to upload the changes from local to remote repository use command `git push`

## Branching
- to create new branch you can use command `git branch <branch-name>`
- to switch to other branch you can use command `git checkout <branch-name>`
- alternatively you can switch to newly created branch using `git checkout -b <branch-name>`

## Merging
- To merge 2 branches, you can use command `git merge`
- you can use command `git diff` to findout the difference between 2 branches
