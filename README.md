# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GIT

chris@Mark-1 MINGW64 ~
$ cd C:\GIT

chris@Mark-1 MINGW64 /c/GIT
$ git clone https://github.com/ch0105/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 12, done.
remote: Counting objects: 100% (12/12), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 12 (delta 2), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (12/12), 4.33 KiB | 4.33 MiB/s, done.
Resolving deltas: 100% (2/2), done.

chris@Mark-1 MINGW64 /c/GIT
$ cd belajarGIT

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout -b Tugas-git
fatal: a branch named 'Tugas-git' already exists

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan isi pada file Tugas-Git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'chris@Mark-1.(none)')

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ ^C

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git config --global user.email "chrismassie111@gmail.com"

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "ch0105"

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan isi pada file Tugas-Git.txt"
[Tugas-git 667dcd5] Menambahkan isi pada file Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-git
Updating 61cb7f7..667dcd5
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 316 bytes | 316.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ch0105/belajarGIT.git
   61cb7f7..667dcd5  main -> main

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan isi pada file Tugas-html.txt"
[Tugas-html 67d1644] Menambahkan isi pada file Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-html
Merge made by the 'ort' strategy.
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 558 bytes | 558.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/ch0105/belajarGIT.git
   667dcd5..47a8449  main -> main

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan isi pada file Tugas-css.txt"
[Tugas-css f3c6de4] Menambahkan isi pada file Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-css
Merge made by the 'ort' strategy.
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 580 bytes | 580.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/ch0105/belajarGIT.git
   47a8449..98590e1  main -> main

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan isi pada file Tugas-js.txt"
[Tugas-js b7f0064] Menambahkan isi pada file Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-js
Merge made by the 'ort' strategy.
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 6c01e42] Menambahkan file Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-midProject
Merge made by the 'ort' strategy.
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 8 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (10/10), 994 bytes | 994.00 KiB/s, done.
Total 10 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), completed with 1 local object.
To https://github.com/ch0105/belajarGIT.git
   98590e1..df6cc6a  main -> main

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan isi pada file Tugas-php.txt"
[Tugas-php 5577fa5] Menambahkan isi pada file Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-php
Merge made by the 'ort' strategy.
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 520 bytes | 520.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/ch0105/belajarGIT.git
   df6cc6a..c6ffdfe  main -> main

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan isi pada file Tugas-finalProject.txt"
[Tugas-finalProject 333edd4] Menambahkan isi pada file Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-finalProject
Merge made by the 'ort' strategy.
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 546 bytes | 546.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/ch0105/belajarGIT.git
   c6ffdfe..2ff71f4  main -> main

chris@Mark-1 MINGW64 /c/GIT/belajarGIT (main)
$


