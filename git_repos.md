
# Repos

## clone
### remote to local
	git clone git@gitlab.dom.com:path/to/repo.git

### local to remote
	git init -b main
	git add .
	git commit -m "Initial commit"
	git remote add origin https://gitlab.dom.com/repo     # remote must be empty
	git push -u origin main

## update
### update local
	git pull
	
### update remote
	git push
