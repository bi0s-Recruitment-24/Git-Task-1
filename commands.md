For cloning: git clone "<link to the repo>" = This command will clone a repository as a whole including the files,commit history etc into our local machine.
Task 2 : 
	1)touch ThejasKrishna - to create a file with name ThejasKrishna
	2)gedit ThejasKrishna - to edit the file 
	3)git add ThejasKrishna - to add the file to the staging area to review and make any changes if needed.
	4)git commit -m "<message>" - to make changes to the repository.
Task 3 :
	1)git checkout -b ThejaskrishnaPT = to create and switch to the new branch ThejaskrishnaPT
Task 4 :
	1)touch ThejaskrishnaPT
	2)gedit ThejaskrishnaPT
Task 5 :
	1)git log -1 = to get the hash of the last commit
	2)gedit ThejaskrishnaPT = to add the hash of the last commit
	3)git commit -m "Added last commit hash to the markdown file" = to commit the changes to the repository
Task 6 :
	git merge ThejaskrishnaPT
Task 7 :
	1)gedit README.md
	2)git commit -m "added name to the README.md file"
	3)git reset --hard HEAD~1 = This command is used to undo the changes to the repo( "--hard" is used to undo the changes done to the repository,'HEAD~1' is used to change the pointer from the current 		commit to previous commit)
	
