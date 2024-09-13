# Fork

This creates a copy of the original repository under your github account.



# clone

"git clone <url>"
This creates a local copy of the entire repository from the url to local machine.

git tree changes: local repository is created and linked to the remote repository.



# To create

"touch <file.txt>" 
create the file.



# Add the file 

"git add <file.txt>" 
stages the file for commit.

git tree changes: The file is added to staging area to be included in next commit



# Commit the text file

""git commit -m "message"""
Commits the staged file to the local repository with the message.

git tree changes:creates a new commit with the file included.



# Create new branch

"git checkout -b <branchname>"
Creates a new branch and then switches the branch to it.

git tree changes: adds a new branch to your git tree.



# To see branches

"git branch"
it lists all local branches.



# Switch branch

"git checkout <branchname>"
switches to the <branchname> branch.

git free changes: updates working directory to switch to the branch <branchname>.



# Merge the branch

"git merge <branchname>"
merge the current branch with branch <branchname> in the command.
git free changes: it merges branches creating a new merge commit.



# To undo the commit

"git reset --soft HEAD~1"
it undo the last commit but it keeps the changes in the working directory thats why "--soft" is used.

git tree changes: removes the last commit but keeps changes for further modification.



# Pushing changes

"git push origin main"

uploads local commits to github.

git tree changes: updates the remote repository with local changes.
