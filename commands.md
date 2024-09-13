#q1)
in order to fork and clone the repository in your local machine one can simply use the command:-git clone (url of the repositary)
it takes the copy of the repository and displays it on the screen.
#q2)
to add a text file into this repository wiht your name as the file name and the content in it should be the date on which u attempted this task and commited it.
the commands used can be:- touch agangashankar(this will create a new file named ganga)
one can use the command cat > filename to write into the file, for example, cat > gangashankar in  this question. in order to track a file one can just use the command:- git add agangashankar...
to modify a file thats present in the local repository one can use the command git commit, for example, in thi question:- git commit -m "date we completed the task"
#q3)
in order to create a branch with our name as branch name, use the command:- git checkout -b aganga@shankar
this will create a new branch named aganga@shankar
#q4)
to create a markdown file in this branch with our name as the filename and the contents being a brief introduction about ourselves, one can use the commands:-
touch agangashankar.md(creates a newmarkdown file)
in order to write into this markdown file one can use the command:-cat > agangashankar.md
to track this markdown file, we have to use the comand, as we did before:-git add agangashankar.md
to make changes in this file use the git commit command, i.e,:-git commit -m "brief introduction"
#q5)
Now on the same markdown file, we are supposed to add the commit hash of the last commit that you had done while adding the text file  and then we have to commit it.
git log hows logs of previous commits.logs are to identify every commit we use.
git add agangashankar.md,it gets tracked now.git commit -m "Brief introduction about myself,hash of last commit".now it accepts the changes and saves it into the local repositary.

#q6)
in order to merge a newly created branch with the crucial branch one can use the commands like:-git checkout main(this will shift us to the main branch).. now to merge, use the command:- git merge aganga@shankar
#q7)
in this question, we are asked to edit the README.md file,by adding our name at the very end of the file, and undo everything weve done.. to approach this question, we can use the following commands:-
git add README.md(to track the file)
after using the git add command , go with with the git commit command to add your name and save :- git commit -m "add my name to README.md"
use git log to show hash of previous commit, to reset back to the old commit, use the command git reset (the url of previous(old) commit).
