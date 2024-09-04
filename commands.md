1. used git clone [github ssh link] to clone the repository onto the local system.

2. created a text file to this repo with my name and the current data as the content using vim command
   used git add --all which confirms the changes made.
   used git commit -m [file name] to commit the file.

3. created a new branch with my name as branch name.
   used git branch [branch name] to make a new branch with my name.
   used git checkout [branch name] to switch to that branch.

4. used touch [file name] to make a markdown file in this branch and used vim [file name] to write
   a brief description of myself.

5. used git log to view all commit hashes made and copied hash of the last commit and added it to
   the markdown file using vim command.

6. used git checkout main to switch branches and used git merge [branch name] to merge branches.

7. used vim command to edit README file and added my name tot he end of the file.
   used git add and git commit commands to commit it.
   undid the last command using git reset --hard HEAD~1 which reverted the last commit made.

8. added commands.md (this file) with description and added it to main branch using git add
   [file name].

9. finally, pushed all changes into my repo and created a pull request to bi0s recruitment repo.
