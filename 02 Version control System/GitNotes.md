###Chapter1:
- $ git config --global user.name “John Doe” (To set Username)
- $ git config --global user.email “john@doe.org” (To set UserEmail)
- $ git config --global color.ui auto (To autoamte the coloue Scheme)
- $ cd <path/to/project/folder> (To change the directory)
- $ git init (To initialize the repository)
- $ git init --bare (inittialize Git without making .git folder and place its files outside)
- $ ls -la (To list down all the contect in your Working Directory)
- $ git add -A <b>OR</b> $ git add . <b>OR</b> $ git add fileName (To add changes to git)
- $ git commit -m “Initial commit" (To Commit your changes)
- $ cd your/development/folder/ (To change your directory)
- $ git clone https://github.com/gittower/git-crash-course.git (To clone data from GitHUb)
- $ git status (To check status of Track & untrack files i:e Stangging area)
- $ git add new-page.html index.html css/*  (To add Specified name to Git )
- $ git commit -m “Implement the new login box” (To Commit your changes)
- $ git log (To check you activity History)

###Chapter2:
- $ git branch contact-form (To create branch by name of Contact-form)
- $ git branch -v (to list down number of branches with little detail)
- $ git status (To check status of Track & untrack files i:e Stangging area)
- $ git stash (To add files as temporary file to clipborad without uploading it into Github)
- $ git status (To check status of Track & untrack files i:e Stangging area)
- $ git stash list (To list down all stash that you added in clipborad)
- $ git checkout contact-form (To move from one brach to another)
- $ git add contact.html (To add files to Git)
- $ git commit -m "Add new contact form" (To Commit your changes)
- $ git log (To check you activity History)
- $ git checkout master (To move from one brach to another)
- $ git merge contact-form (To merge files of contact-form NOTE:To merge files you must have to ib the specified branch in master if to add contact branch to master)
- $ git log(To check you activity History)

###Chapter3:

- $ git remote add origin https://github.com/EnggQasim/test1.git (To set origin where you want to push your dat)
- $ git remote -v (Show number of remote repositories connected to your Working directory)
- $ git branch -va (work same as "$ git remote -v" by giving somr more details )
- $ git fetch origin master (To fetch the changes from main repository)
- $ git fetch origin (To fetch file from origin NOTE: origin is the main master directory the store by github in orgin)
- $ git log origin/master  (To check you activity History of master branch)
- $ git pull (To pull file from origin NOTE: origin is the main master directory the store by github in orgin)
- $ git checkout <branchName> (To move from one brach to another)
- $ git push -u origin <branchName> (To push data to GitHub)
- $ git branch -vva (work same as "$ git remote -va" by giving somr more details )
- $ git branch -d <branchName> (To delete branch )
- $ git branch -dr origin/<branchName> (to delete branch from Origin/ base repository)
  </br>
- $ git remote add origin <link> (To set origin where you want to push your data)
- $ git remote add origin <"clone"> -f
- $ git push origin master(To push data to GitHub) <b>OR</b> git push origin master -f(To push data to GitHub forefully NOTE: we always try to aviod use of this branch)
- $ git clone <repoName> (To clone data from GitHUb)
- $ git pull origin master (To pull file from origin NOTE: origin is the main master directory the store by github in orgin)
  </br>
- $ git push -u origin <branch> -f (push local brach on server)
- $ git push --all -u (push all things on remote server)
- $ git pull --all (pull all data from server)

if you have local colne you can remane by following steps:
- git branch -m master main
- git fetch origin
- git branch -u origin/main main

BY: Qasim Hassan(SMIT04588)