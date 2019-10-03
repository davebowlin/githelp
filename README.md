# Simple GitHub Instructions

1. 	REMOTE:		create repository / or download/clone repository
2. 	REMOTE:		copy the HTTP or SSH link to the repository
3. 	LOCAL:  	create new folder for repository
4. 	LOCAL:  	go into the new folder
5. 	LOCAL:  	`git clone <link to repository>`
6. 	LOCAL:  	create new branch:  `git checkout -b <local-branch-name>`
7. 	LOCAL:  	edit/create/delete the file(s), etc
8. 	LOCAL:  	add the changes to the branch:  `git add .`
9. 	LOCAL: 		`git commit -m " <message here>"`
10. 	LOCAL:		`git push origin <local-branch-name>`
11. 	REMOTE:		go to github, to the repository, and then to  your branch.
			on your branch, click the green button that says
			"Compare and pull request"
12. 	REMOTE:	when someone approves the changes, they will merge it to the master.
13. 	To copy the current remote branch to your local machine (which will overwrite what's there), do this:
 	`git pull origin <remote branch name>`
 	This is handy to keep from deleting and cloning local repos.

You can push to master as well, instead of your branch, so be careful. If you want to push to master, change line 10 above to this:

`git push origin master`

BE CAREFUL doing this, it's always best practice to push to a branch instead, and then it can be merged to master after it's reviewed.
