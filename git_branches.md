 # branches and teamwork
 
 Workflow
 1. Make a branch to commit subtask-changes without disturbing the "teamwork" on the main branch.
 2. Commit (tested) changes.
 3. Open a pull request.
 4. Review the pull request.
 5. Merge the branch with main when the subtask is finished.
 6. Delete the branch.

## branch
Show current branch

	git branch

Create a branch

	git branch NEW_BRANCH

Switch to another branch

	git checkout BRANCH

Merge branch to main

	# add and commit changes on BRANCH
	git checkout main   # switch to main
	git merge BRANCH

Merge conflict

A file contains a changed line on BRANCH and on main

	<<<<<<< HEAD
	# this is a PRO file on branch "main"
	=======
	# this is a MED file on branch "fences"
	>>>>>>> fencing

Delete branch

	git branch -d BRANCH

