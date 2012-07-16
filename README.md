git-workflow-tutorial
=====================

Repo to use for tutorial on how we are using git in scholarsphere

Step 1:
On your local computer cd into working directory (i.e. ~/workspace/ruby)

Step 2:
Clone repo onto local computer
git clone https://github.com/psu-stewardship/git-workflow-tutorial.git git-workflow-tutorial

Step 3: 
cd git-workflow-tutorial

Step 4: 
Log into redmine and find an issue in the git-workflow-tutorial project that you have been assigned

Step 5:
In your local repo create a new branch for this issue
git branch GWT-<ticket-number>

Step 6:
Use new branch
git checkout GWT-<ticket-number>

Step 7: 
Make changes to appropriate files to fix assigned issue

Step 8:
Check to see what files have been updated
git status

Step 9:
Stage changed or newly added files for commit
git add /path/to/file(s)

Step 10: 
Commit changes to local repository
git commit -m "my change is going to solve most things that were broken which is pretty 'sawsome fixes #<ticket-number>"

Step 11:
Back to master branch
git checkout master

Step 12: 
Pull latest version of repo
git pull origin master

Step 13: 
Back to feature branch
git checkout GWT-<ticket-number>

Step 14:
Rebase feature branch
git rebase master

Step 15:
Run tests

Step 16:
Back to master branch
git checkout master

Step 17:
Merge changes from feature branch into master
git merge GWT-<ticket-number>

Step 18:
Run tests

Step 19:
git push


