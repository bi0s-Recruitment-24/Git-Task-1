git clone is used to clone repository to local device.
git clone https://github.com/bi0s-Recruitment-24/Git-Task-1.git

git config --global user.name "devi-bakul"
git config used because we are making changes in the repository for the first time.

cd 'OneDrive - Amrita university'
cd Documents
cd GitHub
cd bi0s
#to get into the local repository directory

touch 'devi.txt'
#used to create a new file in the terminal

vim devi.txt
#used to open the vim editor for writing into devi.txt

mv 'devi.txt' 'devi-bakul.txt'
#to rename the file from devi.txt to devi-bakul.txt

git add 'devi-bakul.txt'
#used to add changes made in devi-bakul.txt to the staging area

git add 'devi-bakul.txt'
#repeated the last statement because LF was not replaced by CRLF

git commit -m "Added Text File devi-bakul.txt"
#commits the changes with a message "Added Text File devi-bakul.txt"

git checkout -b devi-bakul
#used to create a new branch named devi-bakul and switches to the new branch

touch devi-bakul.md
#creates a new file devi-bakul.md

vim devi-bakul.md
#used to make changes to the file devi-bakul.md

git add devi-bakul.md
#puts the file in the staging area so as to commit it

git add devi-bakul.md
#puts it in the stagging area again because LF was not replaced by CRLF

git commit -m "Added Markdown File devi-bakul.md"
#commits the changes with a message "Added Markdown File devi-bakul.md"

git checkout main
#used to switch back to main branch

git log -1 --format=%H
#used to get the commit hash of the latest commit

vim devi-bakul.md
#opens editor to add the commit hash

vim README.md
#opens editor to append name

git add README.md
#puts it in the stagging area

git commit -m "Adding my name to README.md"
#commits the changes to README.md with the message "Adding my name to README.md"

git pull origin main
#to pull all the changes from the remote repository

git merge devi-bakul
#to merge branch devi-bakul with the current branch