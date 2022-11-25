# git_practice

## init
### init repo

	git init


## staging
### stage files

	git add filename

### diff between staged and working
	
	git diff filename


## commit
### commit staged files

	git commit -m "Initial Commit"

### show commit log

	git log      # chronological descend


## backtrack commands
### reset working dir to HEAD
	git checkout HEAD filename
	
### reset/stay with HEAD and untrack staged file
	git reset HEAD filename
	
### reset/move HEAD to "commitSHA" and untrack staged file
	git reset commitSHA filename

