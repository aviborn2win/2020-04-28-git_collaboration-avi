# 2020-04-28-git_collaboration-avi
Git collaboration workshop

- 'git clone' <URL> : downloads the repository from the web to our computer.
	- Make sure you dont nest this command in another repository.
	- just like 'git init' do this only once per repository.


## Branches

- 'git branch <branch name> : create a new branch
- git switch <branch_name> : move to a branch
- git checkout <branch_name> : old way of moving to branch

- git switch -c <branch_ name> : create and move in 1 command
- git checkout -b <branch_name> 

## Pull requests (Online Merge)

- git push origin <branch_name> : pushes branch to the remote
	- this is where you will create the PR (online)
	- merge the PR (aso the branch) by accepting and merging the PR
- dont forget to clean up your branches 
- git fetch --prune : cleans up the refernces in your git  log --oneline --graph --decorate - all
- git branch -d <branch_name> : delete branch on your local machine.
	- it will tell u to move to another branch (ex: master) first

