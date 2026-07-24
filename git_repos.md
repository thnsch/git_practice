
# Repos

## clone
### remote to local
	git clone git@gitlab.dom.com:path/to/repo.git [name of local repo]

### local to remote
	git init -b main
	git add .
	git commit -m "Initial commit"
	git remote add origin https://gitlab.dom.com/repo     # remote must exist and be empty
	git push -u origin main

## update
### update local
	git pull      // git fetch && git merge
	
### update remote
	git push


## configure remote repo
### remote repo URL (authentication method)
Use the URL for ssh authentication

	git remote set-url origin git@github.com:OWNER/REPO.git

Check and confirm

	git remote -v
or

	git config --show-origin --get-regexp 'remote\..*\.url'


