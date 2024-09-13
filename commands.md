# Task 1: Fork and Clone
git clone https://github.com/Harikrishnanspillai/Git-Task-1.git - Clone the repository to the local machine

# Task 2: Add a Text File and Commit
echo. >Harikrishnan_S_Pillai.txt - Create a new text file with the current date as content
git add Harikrishnan_S_Pillai.txt - Add the file to the Git staging area
git commit -m "Added text file with current date" - Commit the changes

# Task 3: Create a New Branch
git branch Harikrishnan_S_Pillai - Create a new branch with your name
git checkout Harikrishnan_S_Pillai - Switch to the new branch

# Task 4: Add a Markdown File and Commit
echo. > Harikrishnan_S_Pillai.md - Create a new markdown file with a brief description and commit hash
git add Harikrishnan_S_Pillai.md - Add the file to the Git staging area
git commit -m "Added markdown file with brief description and commit hash" - Commit the changes

# Task 5: Merge the Branches
git checkout main - Switch back to the main branch
git merge Harikrishnan_S_Pillai - Merge the newly created branch with the main branch

# Task 6: Edit README.md and Undo
git add README.md - Add the file to the Git staging area
git commit -m "Added name to README.md" - Commit the changes
git reset --soft HEAD~1 - Undo the last commit

# Task 7: Add a New File and Commit
echo. > commands.md - Create a new file with Git commands and descriptions
git add commands.md - Add the file to the Git staging area
git commit -m "Added commands.md file" - Commit the changes

# Task 8: Push Changes and Create a Pull Request
git push origin main - Push the changes to your own GitHub repository