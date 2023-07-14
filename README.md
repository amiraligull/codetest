# codetest

1 "git init" command will intialized the git

2 "git status" command will show you tracked and untracked flies

3 "git add ." will move files into tracked zone

4 "git commit -m "" " command will commit (save the changes) and move the files to staging zone

5 "git reset" will convert all tracked files to untracked

6 ".gitignore file" is used to igonre the files that you don,t want to tracked or upload to git

7 "git remote" or "git remote add origin https://github.com/amiraligull/codetest.git"
the above command basically tells the git where have to upload the files on which addres mean on which repo. one more thing you have to provide it only one time when you first push the changes after that you don,t neet run this command again and again.

8 "git pull origin main" this command helps you to get the updated changes in to the repo also you have to run it befor "git push origin main" command than push the code

9 "git push -u origin main" you will run this command when you push the code first time to the repo after that when you want to push code to git repo just run the command "git push origin main"

10 "git clone URL" This command will copy the repo which URL you past

11 "git branch BranchName" this command will help you to create a new branch in repo

12 "git checkout BranchName" this command will move your Head(switched) from one branch to other which you just provide the Branch Name

=========================================
now lets first move to master or main branch so we can see if we have any changes from other branch that we can merge in master or our main branch.
first check the master is fully updated or not by git pull origin main-or-master
after that we move to 13 point bellow.

13 "git branch --merged" than
"git merge BranchName" the branch you want to merge in master or main will merge.

14 than simply push under your main or master branch git push origin Masterormain
