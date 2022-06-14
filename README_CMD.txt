
aliev@Dobby MINGW64 ~/Desktop
$ mkdir my-homework

aliev@Dobby MINGW64 ~/Desktop
$ cd my-homework/

aliev@Dobby MINGW64 ~/Desktop/my-homework
$ touch index.html

aliev@Dobby MINGW64 ~/Desktop/my-homework
$ touch style.css

aliev@Dobby MINGW64 ~/Desktop/my-homework
$ git init
Initialized empty Git repository in C:/Users/aliev/Desktop/my-homework/.git/

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git add index.html

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git commit -m "Index Adding"
[master (root-commit) 29d5388] Index Adding
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git branch -M master

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git remote add origin https://github.com/alievqara/My-Homework.git

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 218 bytes | 218.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/alievqara/My-Homework.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git add style.css

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git commit -m "css complated"
[master ca3f641] css complated
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 style.css

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git branch -M master

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 250 bytes | 250.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/alievqara/My-Homework.git
   29d5388..ca3f641  master -> master
branch 'master' set up to track 'origin/master'.

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git branch myfeature

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git checkout myfeature
Switched to branch 'myfeature'

aliev@Dobby MINGW64 ~/Desktop/my-homework (myfeature)
$ touch script.js

aliev@Dobby MINGW64 ~/Desktop/my-homework (myfeature)
$ git add script.js

aliev@Dobby MINGW64 ~/Desktop/my-homework (myfeature)
$ git commit -m "pleace check script"
[myfeature bcb3a9e] pleace check script
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 script.js

aliev@Dobby MINGW64 ~/Desktop/my-homework (myfeature)
$ git push -u origin myfeature
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 263 bytes | 263.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'myfeature' on GitHub by visiting:
remote:      https://github.com/alievqara/My-Homework/pull/new/myfeature
remote:
To https://github.com/alievqara/My-Homework.git
 * [new branch]      myfeature -> myfeature
branch 'myfeature' set up to track 'origin/myfeature'.

aliev@Dobby MINGW64 ~/Desktop/my-homework (myfeature)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ touch README_CMD.txt

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git add README_CMD.txt

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git commit -m "CMD Komandalar"
[master 2cc9065] CMD Komandalar
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README_CMD.txt

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 271 bytes | 271.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/alievqara/My-Homework.git
   ca3f641..2cc9065  master -> master
branch 'master' set up to track 'origin/master'.

aliev@Dobby MINGW64 ~/Desktop/my-homework (master)
$
