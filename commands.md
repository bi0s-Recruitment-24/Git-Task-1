# Git Commands used
### - Ankith Abhayan (CSE-A)
1.
The git clone command is used to download a remote repository to your own system. 
Here gittask is the folder to which the repo will be downloaded.
```bash
git clone "https://github.com/AnkithAbhayan/Git-Task-1" gittask
```

2.
Here I have created a textfile and it contains today's date.
git add [filename] is used here to add a changed file to the staging area.
After doing so, git commit can be used to commit the changes. Here the -m argument is used to write a commit message.
```bash
git add Ankith.txt
git commit -m "1st commit"
```

3.
git checkout is used to navigate to a branch of one's choosing. I have not created a branch yet.
But by passing the argument '-b' followed by the branch name, I have created a new branch and moved into it, in one command.
The other option would be to do 'git branch Ankith' followed by 'git checkout Ankith'.
```bash
git checkout -b Ankith
```

4.
This step has no git commands
A markdown file was created and a brief description of myself was added using the echo command. 

5.
The following command fetches the commit hash of the most recent commit.
git log is used to access the information of all commits.
The -n parameter can be used followed by an integer to fetch info about an n number of recent commits (here I need 1).
But that still fetches a lot of unnecessary information. To remedy this the --style parameter can be used to display the information you want, the way you want. 
format:"%H" displays just the commit hash, which is what I have to copy and paste to the Ankith.md file. 
%H refers to the commit hash here.
```bash
git log -n 1 --pretty=format:"%H"
```
After adding the commit hash to the end of the file using the echo command, the same commands from step 2 can be used as follows to add the file to the staging area and then commit it.
But since I am on branch 'Ankith', the commits will be made to Ankith and not main.
```bash
git add Ankith.md
git commit -m "added Ankith.md"
```

6.
Here I am navigating to the main branch using git checkout followed by git merge to merge the commit from the branch Ankith to the main branch. Now the main branch will be up-to-date with my new branch.
```bash
git checkout main
git merge Ankith
```

7.
The echo command can be used to append text to the end of the file.
Then I am adding the markdown file to the staging area and commiting it using git add and git commit.
git reset is used to revert to an older commit. The argument HEAD~ is passed to move back one commit, HEAD~2 can be used to move back two commits and so on (HEAD points to the current commit).
```bash
git add README.md
git commit -m "Updated README"
git reset HEAD~
```

8.
touch command is used to create a new file and I'm editing the file right now using a text editor.

9.
The following commands can be used to commit the commands.md file and push the commits that I have made locally into my github repository. 
```bash
git add commands.md
git commit -m "Added commands.md"
git push
```
