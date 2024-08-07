1) After forking the repo, I created a separate directory called Git so that I could clone it. I used the git clone command with the repository's URL using SSH protocol as HTTPS wasn't
working for me, (git clone git@github.com:bi0s-Recruitment-24/Git-Task-1.git) after running this, in my current directory a new directory with the repo's name was created which is 
basically the root of my cloned repository.

2) To add a text file I just used a text editor called "nano", (nano akshith.txt and entered in the date I created the file). Next I added the newly created file to the staging area by 
using the command git add (git add akshith.txt). Later I committed it using the command git commit (git commit -m "I placed in a little message here for reference"). I used the git push
command to push the changes into my forked repo (git push origin main)

3) So instead of first creating the branch using (git branch akshith) and then switching to the branch (git checkout akshith), I just used (git checkout -b akshith) to do all of that
in just a single line. This branch is created so that I could do stuff without affecting the main branch. Once I'm done with my work at the new branch I would just merge it to the
main branch, so that the changes occurred in the new branch is injected into the main branch. I used the git push command to push the changes into my forked repo (git push origin akshith)

4) Just like the 2nd point I created a file called akshith.md and the edited it with the nano text editor (nano akshith.md). Then I added it into the staging area (git add akshith.md)
then committed it (git commit -m "Added in another message"). Again I pushed the changes to my forked repo (git push origin main). I still have the akshith.txt file in the staging area
but even though I have committed the same file more than once, Git doesn't store duplicate data and it compresses files, to be more efficient.

5) Every commit made has a unique hash value, which is just like an ID number, unique to that particular commit. All commit hashes can be accessed by using the command (git log). So I 
copied the hash of the commit made to the akshith.txt file and opened the text editor for the akshith.md file (nano akshith.md) pasted it, added it again to the staging area (git add 
akshith.md) and then committed it (git commit -m "Another tiny message here"). I pushed the changes to the forked repo (git push origin main).

6) Since I'm done with all the stuff in the akshith branch, I'm gonna merge it with the main branch. For that first I switched to the the main branch (git checkout main), alternatively
switch could be used instead of checkout but the command is in its trial stages. Then I merged the 2 branches (git merge akshith). Now the changes made in the branch "akshith" are 
integrated into the main branch. But akshith will still remain in the repo and can always be checked out. I used git branch to find out which branch I'm working with currently.

7) So I opened the README.md file using nano text editor and added my name at the very end. I added it to the staging area and then committed it (git commit -m "LIL MEASSAGE"). So to 
revert this using reset command there are 2 ways, one is --soft reset and the other is --hard reset (I used --hard reset). Soft reset just removes the latest commit hash from the git log
and you won't be able to view the commit but my name will still be there in the README.md file, so it basically keeps the changes for a re-commit. So for completely reverting the edit I 
have to use this command (git reset --hard HEAD~1), HEAD~1 basically refers to the latest commit I made, so it basically discards the commit and doesn't keep the changes for a re-commit.
