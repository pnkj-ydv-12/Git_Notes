# Git_Notes:
Here you find the notes and complete git commands 
* Git -> Git is a Version Control System 
      -> Version COntrol System is a tools that helps to track changes in code.
      -> Popular, Free & Open Source and Fast & 

  Usage-> 1. Track the History
          2. Collaborate

* Github -> Website that allows developers to store and
            manage their code using Git.(folder/Repository)

* Version Check Command -> git --version.

* Configuring Git: (~ -> Home Directory)

-> git config --global user.name "Pankaj Yadav"
-> git config --global user.email "pnkj08ydv@gmail.com"
-> git config --list.

-> cd -> for changing directory.
-> ls -> for printing list of the folder.
-> ls -a -> For printing all the files(including hidden files)

* Clone & Status Command

  1. Clone -> Cloning a repository on our local machine.
           -> Github(Repo)----(Copy)--->Laptop.
     ->git clone <--link-->

 2. Status -> Display the status of the code
     ->git status
            {-> After make changes do commit{Add-Commit}}

* Files:
  
  1.Untracked->new files that git doesn't track yet
  2.Modified->changed
  3.Staged->file is ready to be committed
  4.Unchanged->unchanged

* Add & Commit Command

  1. Add - adds new or changed files in your working directory to the Git staging area.
  -> git add <-file name->
  -> git add .

  2. Commit- It is the record of change
  -> git commit -m "some message"

* PUSH Command :
  
  1. push -> upload local repo content to remote repo{local----push--->remote}
  -> git push origin main

* INIT Command:
  
  1. init -> used to create a new git repo
  ->git init 
  ->git remote add origin <--link-->
  ->git remote -v(to verify remote)
  ->git branch
  ->git branch -M main (to rename branch)
  ->git push origin main
