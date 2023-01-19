Git is a version control system
Git helps you to keeel trach of code changes
Git is used to collaborate with other developers

git add => add file to staging area
to use git add, 'git add <flle_name>'

to unstage => git rm --cached <file>

git status => show status of working directory and staging area

git commit => commit changes to local repo

git push => push changes to remote repo
to use the command, 'git push'

<!-- create a new repository to github and push your code to it -->

to point our locl repository to github=>
'git remote add origin https://github.com/Akpo-Fure/sq15.git'

initialie our current base branch to main: 'git branch -M main'

to push our local repo to github ==> 'git push -u origin main'

<!-- whenever you male change to your project, follow this process to push to github-->

'git add .'
'git commit -m 'your commit message''
'git push'

<!-- to pull changes from github -->

'git pull' => pull changes from github(remote server) to local machine

<!-- Branchng -->

## A branch is a new/serperatr version of the main repository

'git branch' ==> show all branches

'git branch <branch_name>' => create a new branch

'git checkout <branch_name>' => switch to a branch
