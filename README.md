# This is how you do the branch stuff

From master on GitBash, with a clean working tree, make the new branch:

    git checkout -b <branch_name>

Make changes to the branch, add/commit, push the branch to GitHub:

    git push origin <branch_name>

go to GitHub and merge the branch to master.

What happens now  is the master timeline in GitHub is ahead of the local timeline on your device. So we need to pull from GitHub:

in master: git pull origin master
