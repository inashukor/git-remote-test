# git-remote-test
Repository to try git remote

1. Clone repo into local computer. Open git bash, directed to desktop
                
                1- $ git clone https://github.com/inashukor/git-remote-test.git
                  Cloning into 'git-remote-test'...
                  remote: Enumerating objects: 3, done.
                  remote: Counting objects: 100% (3/3), done.
                  remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
                  Receiving objects: 100% (3/3), done.
              2- $ git status
                  On branch main
                  Your branch is up to date with 'origin/main'.
                  
             3- $ git log --all --decorate --oneline --graph
                * f3ca67c (HEAD -> main, origin/main, origin/HEAD) Initial commit
                
on the local computer branch name is origin.
example : add new file on local computer name "index.html" and save

             4- $ git status (index.html still at the working area, so we need to add into staging area)
             5- $ git add . 
             6- $ git commit -m "menambahkan file index.html"
             7- $ git status (branch in our local computer have extra 1 commit than origin/master)
             8- $ git push (push into github)
             9- $ git status
             10- $ git log --all --decorate --oneline --graph

check username & user email 
$ git config --list , to end type ":q"
to switch the user
$ git config --global user.name "alia"
$ git config --global user.email "alia232.gmail.com"
