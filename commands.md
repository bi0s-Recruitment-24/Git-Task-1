1. git clone https://github.com/Karthikpillai77/Git-Task-1.git  

   To clone the repository to local machine.  

2. git add karthik.txt
   
To add file karthik.txt to the staging area.  

3. git commit -m "added text file"
   
   To commit the changes in the repository.The "commit" command is used to save your changes to the local repository 

4. git checkout -b karthik 
 
To create a new branch name karthik and switch to that branch.

5. git log  

To display the commit history.  

6. git checkout main
  
  To switch to the main branch.  

7. git merge karthik  

To merge the karthik branch to main branch. The changes made in karthik branch is copied to main branch.  

8. git reset HEAD^

   The command undoes the last commit. This means the current branch pointer (HEAD) moves back one commit.


9. git restore

  Reverts the changes in the specified file in the working directory to match the latest commit. If the file has been modified, these changes will be discarded.
