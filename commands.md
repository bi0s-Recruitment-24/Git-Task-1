# Git-Commands
1. First we forked the respository and using the git **clone** command with the url of the respository I cloned the Git-Task to my repository.
2. I created a text named 'sanjay-viswakarma-hs" and put today's date as the content of the file and I commited this text file to the main branch by first adding this text file to the staging area with the command **git add "sanjay-viswakarma-hs** and then I commited it using git **commit -m**.
3. I created a new branch with the command git **branch sanjay**(sanjay as my branch name).
4. By using the command git **checkout sanjay** I will be swtiched to the branch 'sanjay' from the 'main' branch. Using the touch command I created a markdown file named "sanjay-viswakarma-hs".
5. First I switched back to the main branch by using the command git **checkout sanjay**. Then by using the git **log** , it displays the changes made in the branches, from that I copied the commit id for the commit I made for the text file commited and put this in the sanjay-viswakarma-hs.md. Then I switched back to the main branch again and from there I used git add "sanjay-viswakarma-hs.md" and git commit to commit this md file.
6. First I switched to the main branch using checkout command. Then by using the command git **merge sanjay** the 'sanjay branch gets merged with the main branch.
7. First I edited the README.md text and put my name at the end of the file and using git add then git commit to the 'main' branch.
Then to undo this change I made I copied the commit ID last commit  I made, which was the merging of the branches and used the command git **reset** (the commit ID).
