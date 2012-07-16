git-workflow-tutorial
=====================

Repo to use for tutorial on how we are using git in scholarsphere


1. On your local computer cd into working directory (i.e. ~/workspace/ruby)

2. Clone repo onto local computer

    git clone https://github.com/psu-stewardship/git-workflow-tutorial.git git-workflow-tutorial

3. Change into working directory

    cd git-workflow-tutorial

4. Log into redmine and find an issue in the git-workflow-tutorial project that you have been assigned

5. In your local repo create a new branch for this issue

    git branch GWT-&lt;ticket-number&gt;

6. Use new branch

    git checkout GWT-&lt;ticket-number&gt;

7. Make changes to appropriate files to fix assigned issue

8. Check to see what files have been updated

    git status

9. Stage changed or newly added files for commit

    git add /path/to/file(s)

10. Commit changes to local repository

    git commit -m "my change is going to solve most things that were broken which is pretty 'sawsome fixes #<ticket-number>"

11. Back to master branch

    git checkout master

12. Pull latest version of repo

    git pull origin master

13. Back to feature branch

    git checkout GWT-&lt;ticket-number&gt;

14. Rebase feature branch

    git rebase master

15. Run tests

16. Back to master branch

    git checkout master

17. Merge changes from feature branch into master

    git merge GWT-&lt;ticket-number&gt;

18. Run tests

19. Update remote repo

    git push


