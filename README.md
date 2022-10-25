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

### Exercise 2

```bash 
- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout main
Switched to branch 'main'

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git pull origin main
From https://github.com/iamzilfa/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
Updating c96f10f..fd06359
Fast-forward
 services.html | 12 ++++++++++++
 1 file changed, 12 insertions(+)
 create mode 100644 services.html

ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m 'service file modified'
[ft/service-redesign f0fe9e6] service file modified
 1 file changed, 1 insertion(+)
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin ft/service-redesign 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 326 bytes | 326.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/iamzilfa/Gym-Git-Exercise-Solutions/pull/new/ft/service-redesign
remote: 
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout main 
Switched to branch 'main'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch
  dev
  ft/bundle-2
  ft/service-redesign
* main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m "changes made on service file on main branch"
[main 8bd6e97] changes made on service file on main branch
 1 file changed, 1 insertion(+)
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin main 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 336 bytes | 336.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
   fd06359..8bd6e97  main -> main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout ft/service-redesign 
Switched to branch 'ft/service-redesign'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git merge --abort 
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git diff
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch 
  dev
  ft/bundle-2
* ft/service-redesign
  main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git diff
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git diff  main ft/service-redesign
diff --git a/services.html b/services.html
index 811a318..e00f4dd 100644
--- a/services.html
+++ b/services.html
@@ -8,6 +8,6 @@
 </head>
 <body>
     <h1>Here we're providing good services</h1>
-    <p>You're all welcomed</p>
+    <p>You're going to enjoy</p>
 </body>
 </html>
\ No newline at end of file

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git merge
fatal: No remote for the current branch.

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git pus
git: 'pus' is not a git command. See 'git --help'.

The most similar commands are
	push
	pull
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin ft/service-redesign
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Everything up-to-date

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch ft/service-redesign
You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
	both modified:   services.html

no changes added to commit (use "git add" and/or "git commit -a")

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m 'conflicts merged'
[ft/service-redesign 6dc11e2] conflicts merged

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin ft/service-redesign
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 332 bytes | 332.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
   f0fe9e6..6dc11e2  ft/service-redesign -> ft/service-redesign

- ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout main 
Switched to branch 'main'


```


## Bundle 3

### Exercise 1

```bash

ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add team.html
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m 'creating team file'
[ft/team-page 3446165] creating team file
 1 file changed, 12 insertions(+)
 create mode 100644 team.html
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch ft/team-page
nothing to commit, working tree clean
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin team.html
error: src refspec team.html does not match any
error: failed to push some refs to 'https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin ft/team-page 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 476 bytes | 476.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/iamzilfa/Gym-Git-Exercise-Solutions/pull/new/ft/team-page
remote: 
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/team-page -> ft/team-page
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout main 
Switched to branch 'main'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout ft/team-page 
Switched to branch 'ft/team-page'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git log
commit 3446165d5dadaf6cfe1037fe528ca87902c9f56c (HEAD -> ft/team-page, origin/ft/team-page)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:52:05 2022 +0200

    creating team file

commit 7ccfb67656a9f87bb5ac972589ad8d4e36317f07 (origin/main, main, ft/contact-page)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:49:34 2022 +0200

    READMI modified

commit 8bd6e97bcb6dabc8a6af969866a0fae00622cb57
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:04:22 2022 +0200

    changes made on service file on main branch

commit fd06359c44dccefbd400c68158dc9b8fc7aeb704
Merge: c96f10f ecbcd1f
Author: Zilfa CYAMANI <71026985+iamzilfa@users.noreply.github.com>

[1]+  Stopped                 git log
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout ft/contact-page 
Switched to branch 'ft/contact-page'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git cherry-pick 3446165d5dadaf6cfe1037fe528ca87902c9f56c
[ft/contact-page 90f09fb] creating team file
 Date: Tue Oct 25 14:52:05 2022 +0200
 1 file changed, 12 insertions(+)
 create mode 100644 team.html
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add contact.html
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m 'adding contact file'
[ft/contact-page 9864e9e] adding contact file
 1 file changed, 12 insertions(+)
 create mode 100644 contact.html
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin ft/contact-page 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 765 bytes | 765.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/iamzilfa/Gym-Git-Exercise-Solutions/pull/new/ft/contact-page
remote: 
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/contact-page -> ft/contact-page
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch
  dev
  ft/bundle-2
* ft/contact-page
  ft/service-redesign
  ft/team-page
  main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin ft/faq-page 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Total 0 (delta 0), reused 0 (delta 0)
remote: 
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/iamzilfa/Gym-Git-Exercise-Solutions/pull/new/ft/faq-page
remote: 
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/faq-page -> ft/faq-page
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git log
commit 9864e9ed639937ac941b494d8b86be1ad00403e4 (HEAD -> ft/faq-page, origin/ft/faq-page, origin/ft/contact-page, ft/contact-page)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 15:06:37 2022 +0200

    adding contact file

commit 90f09fbe8299d06d805af232fb9f381db609bc38
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:52:05 2022 +0200

    creating team file

commit 7ccfb67656a9f87bb5ac972589ad8d4e36317f07 (origin/main, main)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:49:34 2022 +0200

    READMI modified

commit 8bd6e97bcb6dabc8a6af969866a0fae00622cb57
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:04:22 2022 +0200

[2]+  Stopped                 git log
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git revert 90f09fbe8299d06d805af232fb9f381db609bc38
Removing team.html
[ft/faq-page a09bc60] Revert "creating team file"
 1 file changed, 12 deletions(-)
 delete mode 100644 team.html
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git log
commit a09bc606740f3ba8b2653f0477b6e91313c3420f (HEAD -> ft/faq-page)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 16:55:18 2022 +0200

    Revert "creating team file"
    
    This reverts commit 90f09fbe8299d06d805af232fb9f381db609bc38.

commit 9864e9ed639937ac941b494d8b86be1ad00403e4 (origin/ft/faq-page, origin/ft/contact-page, ft/contact-page)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 15:06:37 2022 +0200

    adding contact file

commit 90f09fbe8299d06d805af232fb9f381db609bc38
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:52:05 2022 +0200

    creating team file

commit 7ccfb67656a9f87bb5ac972589ad8d4e36317f07 (origin/main, main)
:...skipping...
commit a09bc606740f3ba8b2653f0477b6e91313c3420f (HEAD -> ft/faq-page)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 16:55:18 2022 +0200

    Revert "creating team file"
    
    This reverts commit 90f09fbe8299d06d805af232fb9f381db609bc38.

commit 9864e9ed639937ac941b494d8b86be1ad00403e4 (origin/ft/faq-page, origin/ft/contact-page, ft/contact-page)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 15:06:37 2022 +0200

    adding contact file

commit 90f09fbe8299d06d805af232fb9f381db609bc38
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:52:05 2022 +0200

    creating team file

commit 7ccfb67656a9f87bb5ac972589ad8d4e36317f07 (origin/main, main)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:49:34 2022 +0200

    READMI modified

commit 8bd6e97bcb6dabc8a6af969866a0fae00622cb57
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:04:22 2022 +0200

    changes made on service file on main branch

commit fd06359c44dccefbd400c68158dc9b8fc7aeb704
Merge: c96f10f ecbcd1f
Author: Zilfa CYAMANI <71026985+iamzilfa@users.noreply.github.com>
Date:   Tue Oct 25 13:09:39 2022 +0200

    Merge pull request #1 from iamzilfa/ft/bundle-2
:




































commit a09bc606740f3ba8b2653f0477b6e91313c3420f (HEAD -> ft/faq-page)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 16:55:18 2022 +0200

    Revert "creating team file"
    
    This reverts commit 90f09fbe8299d06d805af232fb9f381db609bc38.

commit 9864e9ed639937ac941b494d8b86be1ad00403e4 (origin/ft/faq-page, origin/ft/contact-page, ft/contact-page)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 15:06:37 2022 +0200

    adding contact file

commit 90f09fbe8299d06d805af232fb9f381db609bc38
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:52:05 2022 +0200

    creating team file

commit 7ccfb67656a9f87bb5ac972589ad8d4e36317f07 (origin/main, main)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:49:34 2022 +0200

    READMI modified

commit 8bd6e97bcb6dabc8a6af969866a0fae00622cb57
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:04:22 2022 +0200

    changes made on service file on main branch

commit fd06359c44dccefbd400c68158dc9b8fc7aeb704
Merge: c96f10f ecbcd1f
Author: Zilfa CYAMANI <71026985+iamzilfa@users.noreply.github.com>
:




















commit a09bc606740f3ba8b2653f0477b6e91313c3420f (HEAD -> ft/faq-page)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 16:55:18 2022 +0200

    Revert "creating team file"
    
    This reverts commit 90f09fbe8299d06d805af232fb9f381db609bc38.

commit 9864e9ed639937ac941b494d8b86be1ad00403e4 (origin/ft/faq-page, origin/ft/contact-page, ft/contact-page)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 15:06:37 2022 +0200

    adding contact file

commit 90f09fbe8299d06d805af232fb9f381db609bc38
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:52:05 2022 +0200

:






















commit a09bc606740f3ba8b2653f0477b6e91313c3420f (HEAD -> ft/faq-page)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 16:55:18 2022 +0200

    Revert "creating team file"
    
    This reverts commit 90f09fbe8299d06d805af232fb9f381db609bc38.

commit 9864e9ed639937ac941b494d8b86be1ad00403e4 (origin/ft/faq-page, origin/ft/contact-page, ft/contact-page)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 15:06:37 2022 +0200

    adding contact file

commit 90f09fbe8299d06d805af232fb9f381db609bc38
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 14:52:05 2022 +0200

    creating team file


[3]+  Stopped                 git log
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin ft/faq-page 
Username for 'https://github.com': ^Z
[4]+  Stopped                 git push origin ft/faq-page
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch ft/faq-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	faq.html

nothing added to commit but untracked files present (use "git add" to track)
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin ft/faq-page 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 270 bytes | 270.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
   9864e9e..a09bc60  ft/faq-page -> ft/faq-page



```


### Exercise 2

```bash

ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout ft/faq-page 
Switched to branch 'ft/faq-page'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch
  dev
  ft/bundle-2
  ft/contact-page
  ft/faq-page
* ft/home-page-redesign
  ft/service-redesign
  ft/team-page
  main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout main 
Switched to branch 'main'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m 'home file modified'
[main 5b324b5] home file modified
 1 file changed, 1 insertion(+)
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin main 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 325 bytes | 325.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
   11cd49f..5b324b5  main -> main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git rebase main
First, rewinding head to replay your work on top of it...
Applying: creating team file
Applying: adding contact file
Applying: Revert "creating team file"
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch 
  dev
  ft/bundle-2
  ft/contact-page
  ft/faq-page
* ft/home-page-redesign
  ft/service-redesign
  ft/team-page
  main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch ft/home-page-redesign
nothing to commit, working tree clean
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m 'home file modified'
[ft/home-page-redesign 2888a33] home file modified
 1 file changed, 6 insertions(+)
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin ft/home-page-redesign 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 4 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (11/11), 1.29 KiB | 1.29 MiB/s, done.
Total 11 (delta 6), reused 0 (delta 0)
remote: Resolving deltas: 100% (6/6), completed with 2 local objects.
remote: 
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/iamzilfa/Gym-Git-Exercise-Solutions/pull/new/ft/home-page-redesign
remote: 
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign



```

## Bundle 4

### Exercise 1

```bash

ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout main
Already on 'main'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git remote add git-copy https://github.com/iamzilfa/Git-Exercise.git
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git remote -v
git-copy	https://github.com/iamzilfa/Git-Exercise.git (fetch)
git-copy	https://github.com/iamzilfa/Git-Exercise.git (push)
origin	https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git (fetch)
origin	https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git (push)
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   faq.html

no changes added to commit (use "git add" and/or "git commit -a")
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add faq file modied
fatal: pathspec 'faq' did not match any files
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m 'faq file modified'
[main 92445ad] faq file modified
 1 file changed, 1 insertion(+)
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin 
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin main
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 334 bytes | 334.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
   268b143..92445ad  main -> main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push git-copy main
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 43, done.
Counting objects: 100% (43/43), done.
Delta compression using up to 4 threads
Compressing objects: 100% (38/38), done.
Writing objects: 100% (43/43), 8.53 KiB | 2.13 MiB/s, done.
Total 43 (delta 18), reused 0 (delta 0)
remote: Resolving deltas: 100% (18/18), done.
To https://github.com/iamzilfa/Git-Exercise.git
 * [new branch]      main -> main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ 


```

### Exercise 2

```bash

ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout -b ft/footer
Switched to a new branch 'ft/footer'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch 
  dev
  ft/bundle-2
  ft/contact-page
  ft/faq-page
* ft/footer
  ft/home-page-redesign
  ft/service-redesign
  ft/team-page
  main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit 'footer file created'
error: pathspec 'footer file created' did not match any file(s) known to git
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit 'footer file modified'
error: pathspec 'footer file modified' did not match any file(s) known to git
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch ft/footer
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   footer.html

ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m 'footer.html'
[ft/footer 4fd170f] footer.html
 1 file changed, 21 insertions(+)
 create mode 100644 footer.html
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m 'footer file modified'
[ft/footer 02389ac] footer file modified
 1 file changed, 4 insertions(+)
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin main 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Everything up-to-date
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin ft/f
ft/faq-page   ft/footer     
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin ft/footer 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 787 bytes | 787.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/iamzilfa/Gym-Git-Exercise-Solutions/pull/new/ft/footer
remote: 
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/footer -> ft/footer
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout main
Switched to branch 'main'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git merge --squash ft/footer
Updating c67937d..02389ac
Fast-forward
Squash commit -- not updating HEAD
 footer.html | 25 +++++++++++++++++++++++++
 1 file changed, 25 insertions(+)
 create mode 100644 footer.html
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git log
commit c67937d6ac55f11ec031a4b4b73795d892a1dce2 (HEAD -> ft/squashing, origin/main, git-copy/main, main)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 17:59:08 2022 +0200

    README modified

commit 92445adf5f574e9ee29488eac05a0522c1285e70
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 17:49:49 2022 +0200

    faq file modified

commit 268b143914219f953e8789d35234098ca321d92f
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 17:40:29 2022 +0200


[5]+  Stopped                 git log
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch ft/squashing
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   footer.html

ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m "footer changes squashing"
[ft/squashing 8c33f3f] footer changes squashing
 1 file changed, 25 insertions(+)
 create mode 100644 footer.html
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git log
commit 8c33f3f783fa23ea425af4f8b5cd0240b7b2907c (HEAD -> ft/squashing)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 18:20:01 2022 +0200

    footer changes squashing

commit c67937d6ac55f11ec031a4b4b73795d892a1dce2 (origin/main, git-copy/main, main)
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 17:59:08 2022 +0200

    README modified

commit 92445adf5f574e9ee29488eac05a0522c1285e70
Author: iamzilfa <zilcyam@gmail.com>
Date:   Tue Oct 25 17:49:49 2022 +0200


[6]+  Stopped                 git log
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch ft/squashing
nothing to commit, working tree clean
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin ft/squashing 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 550 bytes | 550.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/iamzilfa/Gym-Git-Exercise-Solutions/pull/new/ft/squashing
remote: 
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/squashing -> ft/squashing


```

## Bundle 5

### Exercise 1

```bash

ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git branch
  dev
  ft/bundle-2
  ft/contact-page
  ft/faq-page
  ft/footer
  ft/home-page-redesign
  ft/service-redesign
  ft/squashing
  ft/team-page
* main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch main
nothing to commit, working tree clean
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git pull
fatal: unable to access 'https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git/': Could not resolve host: github.com
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> main

ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git pull main
fatal: 'main' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git pull origin main 
From https://github.com/iamzilfa/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
Already up to date.
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git status
On branch main
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	deleted:    home.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	index.html

no changes added to commit (use "git add" and/or "git commit -a")
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git add .
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git commit -m 'home modified into index'
[main 7face87] home modified into index
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename home.html => index.html (100%)
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ git push origin main 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 231 bytes | 231.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/iamzilfa/Gym-Git-Exercise-Solutions.git
   807e230..7face87  main -> main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ 


```

### Exercise 2

```bash

ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-exercises$ cd ..
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents$ git clone https://github.com/iamzilfa/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
fatal: unable to access 'https://github.com/iamzilfa/git-cafe-exercise.git/': Could not resolve host: github.com
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents$ git clone https://github.com/iamzilfa/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
fatal: unable to access 'https://github.com/iamzilfa/git-cafe-exercise.git/': Could not resolve host: github.com
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents$ git clone https://github.com/iamzilfa/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (107/107), done.
remote: Compressing objects: 100% (101/101), done.
remote: Total 107 (delta 5), reused 104 (delta 4), pack-reused 0
Receiving objects: 100% (107/107), 1.95 MiB | 383.00 KiB/s, done.
Resolving deltas: 100% (5/5), done.
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents$ cd git-cafe-exercise/
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-cafe-exercise$ code .
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-cafe-exercise$ git add .
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-cafe-exercise$ git commit -m 'index file modified'
[main 1c3c319] index file modified
 1 file changed, 1 insertion(+), 1 deletion(-)
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-cafe-exercise$ git branch
* main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-cafe-exercise$ git push origin main 
fatal: unable to access 'https://github.com/iamzilfa/git-cafe-exercise.git/': Could not resolve host: github.com
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-cafe-exercise$ git push origin main 
fatal: unable to access 'https://github.com/iamzilfa/git-cafe-exercise.git/': Could not resolve host: github.com
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-cafe-exercise$ git push origin main 
Username for 'https://github.com': iamzilfa
Password for 'https://iamzilfa@github.com': 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 316 bytes | 316.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/iamzilfa/git-cafe-exercise.git
   d1d3f9c..1c3c319  main -> main
ubuntu@ubuntu-HP-EliteBook-Folio-9480m:~/Documents/git-cafe-exercise$ 


```