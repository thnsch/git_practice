# git commands

## init
### init repo

	git init


## staging to the "index"
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
### reset changes in "working" from HEAD
	git restore filename

### reset changes in "staging" from HEAD
	git restore --staged filename

### reset working dir from HEAD and unstage file
	git checkout HEAD filename
	
### reset from HEAD and unstage file
	git reset HEAD filename
	
### move HEAD to "commitSHA" and unstage file
	git reset commitSHA filename


