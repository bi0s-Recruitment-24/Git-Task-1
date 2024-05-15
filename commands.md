git clone https://github.com/Xhackers7/Git-Task-1 .	-	clones the repo to the current directory
git add .	-	stages the changes made to be commited
git commit -m "Added txt file"	-	commits the changes made with the message "Added txt file"
git branch sreyas		-	creates a new branch named sreyas
git switch sreyas		-	switches to the branch named sreyas
git log --all	-	gives the details of all commits across all branches
git add .
git commit -m "Added md file"
git switch main
git merge sreyas	-	merges the branch named sreyas to the current branch(main)
git add .
git commit -m "Edited readme"
git log --all
git reset 74abee77c1ecc435e785e979f6b7e866edfbd2b2	-	discards all changes and reverts back to the commit given