Setup
-----------

	cd <folder_of_your_choice>
	
	git clone https://github.com/Tarwine/otroniconJam.git
	
	cd otroniconJam
	
	git remote add upstream https://github.com/Tarwine/otroniconJam.git
	
	git fetch upstream master
	
	
Main use cases
------------

Pushing to master

	git status
	
	git add --all
	
	git commit -m "<message_describing_changes>"
	
	git push upstream master
	
	
Pulling from master

	git fetch upstream
	
	git merge upstream/master
	
Discarding local changes
	
	git stash save --keep-index
	
	git stash drop
	

Possibly Unused (Branches)
------------

Creating a branch

	git branch <name_of_your_branch>
	
	git push --set-upstream upstream <name_of_your_branch>
	

Switching branches

	git checkout <name_of_your_branch>
	
	
Pushing to current branch

	git status
	
	git add --all
	
	git commit -m "<message>"
	
	git push upstream <name_of_your_branch>
	
	
Pulling from branch

	git fetch upstream
	
	git merge upstream/<name_of_your_branch>
	

Deleting a branch locally

	git branch -d <name_of_your_branch>
	
	
Refreshing remote branches

	git remote prune upstream
	

Oculus Config

	https://dl.dropboxusercontent.com/u/68381796/OculusConfigUtil.7z
