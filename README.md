# Git Exercises

## Bundle 1

### Exercise 1

```bash


- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents$ mkdir git-exercises

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents$ cd git-exercise

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercise$ git init
Reinitialized existing Git repository in /home/

- ubuntu/Documents/git-exercise/.git/

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercise$ touch README.md

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercise$ git branch
  dev
  main
* test

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercise$ cd ..

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents$ git branch 

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents$ mkdir
mkdir: missing operand
Try 'mkdir --help' for more information.

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents$ mkdir git-exercises
mkdir: cannot create directory ‘git-exercises’: File exists

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents$ cd git-exercises

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch 

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ ls

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git init
Initialized empty Git repository in /home/ubuntu/Documents/git-exercises/.git/

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ touch README.md

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch 

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch 

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m 'First commit'
[master (root-commit) 9a0792c] First commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch 
* master

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch -M main

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch main
nothing to commit, working tree clean

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ code .

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m 'adding some contents to README file'
[main bf7d737] adding some contents to README file
 1 file changed, 6 insertions(+)

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git remote add origin https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin main 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (6/6), 476 bytes | 476.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0)
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout -b dev
Switched to a new branch 'dev'

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch 
* dev
  main

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin dev 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Total 0 (delta 0), reused 0 (delta 0)
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/iamzilfa/Gym-Git-Exercise-Solutions/pull/new/dev
remote: 
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
 * [new branch]      dev -> dev

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout -b test
Switched to a new branch 'test'

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin test 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Total 0 (delta 0), reused 0 (delta 0)
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/iamzilfa/Gym-Git-Exercise-Solutions/pull/new/test
remote: 
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
 * [new branch]      test -> test

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout dev
Switched to branch 'dev'

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch 
* dev
  main
  test

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch -delete test
error: did you mean `--delete` (with two dashes)?

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch --delete test
Deleted branch test (was bf7d737).

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch 
* dev
  main

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin --delete test
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
 - [deleted]         test

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ 


```

### Exercise 2

```bash

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	home.html

nothing added to commit but untracked files present (use "git add" to track)

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add home.html

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash list 

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash 
Saved working directory and index state WIP on main: f3356c7 README changes

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash list 
stash@{0}: WIP on main: f3356c7 README changes

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	about.html

nothing added to commit but untracked files present (use "git add" to track)

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add about.html

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash 
Saved working directory and index state WIP on main: f3356c7 README changes

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash list 
stash@{0}: WIP on main: f3356c7 README changes
stash@{1}: WIP on main: f3356c7 README changes

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add team.html

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash 
Saved working directory and index state WIP on main: f3356c7 README changes

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash status
fatal: unknown subcommand: status

usage: git stash list [<options>]
   or: git stash show [<options>] [<stash>]
   or: git stash drop [-q|--quiet] [<stash>]
   or: git stash ( pop | apply ) [--index] [-q|--quiet] [<stash>]
   or: git stash branch <branchname> [<stash>]
   or: git stash clear
   or: git stash [push [-p|--patch] [-k|--[no-]keep-index] [-q|--quiet]
          [-u|--include-untracked] [-a|--all] [-m|--message <message>]
          [--] [<pathspec>...]]
   or: git stash save [-p|--patch] [-k|--[no-]keep-index] [-q|--quiet]
          [-u|--include-untracked] [-a|--all] [<message>]

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash list 
stash@{0}: WIP on main: f3356c7 README changes
stash@{1}: WIP on main: f3356c7 README changes
stash@{2}: WIP on main: f3356c7 README changes

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash pop stash@{1}
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   about.html

Dropped stash@{1} (564f43afbf9891686f1298a07e43bfe434efc309)

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash list 
stash@{0}: WIP on main: f3356c7 README changes
stash@{1}: WIP on main: f3356c7 README changes

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash pop stash@{1}
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   about.html
	new file:   home.html

Dropped stash@{1} (085a992ff93c323dfc8c187c5832a94de21000f5)

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   about.html
	new file:   home.html

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   about.html
	new file:   home.html

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m "home and about pages"
[main 1d92e60] home and about pages
 2 files changed, 24 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin main 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 558 bytes | 558.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
   f3356c7..1d92e60  main -> main

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash list 
stash@{0}: WIP on main: f3356c7 README changes

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash pop 
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   team.html

Dropped refs/stash@{0} (b5f4a12a350106cff0bf60b10a44e0dfad93daca)

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git reset --hard 
HEAD is now at 1d92e60 home and about pages

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git stash list 

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ 

```


## Bundle 2

### Exercise 1

```bash

ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$  git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch 
  dev
* ft/bundle-2
  main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch ft/bundle-2
nothing to commit, working tree clean
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch ft/bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	services.html

nothing added to commit but untracked files present (use "git add" to track)
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add services.html
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch ft/bundle-2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   services.html

ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m 'set up services page'
[ft/bundle-2 ecbcd1f] set up services page
 1 file changed, 12 insertions(+)
 create mode 100644 services.html
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin ft/bundle-2 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 484 bytes | 484.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/iamzilfa/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
remote: 
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2



```