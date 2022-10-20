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