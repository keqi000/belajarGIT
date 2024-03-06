# belajarGIT

Tempat latihan
Daftar tugas / branch

1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

   Daftar perintah GiT
   …
   asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git
   $ git clone https://github.com/keqi000/belajarGIT.git
   Cloning into 'belajarGIT'...
   remote: Enumerating objects: 6, done.
   remote: Counting objects: 100% (6/6), done.
   remote: Compressing objects: 100% (3/3), done.
   remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
   Receiving objects: 100% (6/6), done.

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git
$ cd belajarGIT

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git branch Tugas-git

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-git)
$ git commit -m "menambah file tugas-git.txt"
[Tugas-git ecf7620] menambah file tugas-git.txt
1 file changed, 1 insertion(+)
create mode 100644 Tugas-Git.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git merge Tugas-git
Updating 42f7567..ecf7620
Fast-forward
Tugas-Git.txt | 1 +
1 file changed, 1 insertion(+)
create mode 100644 Tugas-Git.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 301 bytes | 301.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/keqi000/belajarGIT.git
42f7567..ecf7620 main -> main

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git branch Tugas-html

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-html)
$ git commit -m "menambah file tugas-html.txt"
[Tugas-html 2bae5b8] menambah file tugas-html.txt
1 file changed, 1 insertion(+)
create mode 100644 Tugas-Html.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git merge Tugas-html
Updating ecf7620..2bae5b8
Fast-forward
Tugas-Html.txt | 1 +
1 file changed, 1 insertion(+)
create mode 100644 Tugas-Html.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 333 bytes | 333.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/keqi000/belajarGIT.git
ecf7620..2bae5b8 main -> main

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git branch Tugas-css

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-css)
$ touch Tugas-Css.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-css)
$ git commit -m "menambahkan file tugas-css.txt"
[Tugas-css 5f0cef5] menambahkan file tugas-css.txt
1 file changed, 1 insertion(+)
create mode 100644 Tugas-Css.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git merge Tugas-css
Updating 2bae5b8..5f0cef5
Fast-forward
Tugas-Css.txt | 1 +
1 file changed, 1 insertion(+)
create mode 100644 Tugas-Css.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 360 bytes | 360.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/keqi000/belajarGIT.git
2bae5b8..5f0cef5 main -> main

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git branch Tugas-js

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-js)
$ touch Tugas-Js.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-js)
$ git commit -m "menambah file tugas-js.txt"
[Tugas-js 4f0dfcd] menambah file tugas-js.txt
1 file changed, 1 insertion(+)
create mode 100644 Tugas-Js.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git merge Tugas-js
Updating 5f0cef5..4f0dfcd
Fast-forward
Tugas-Js.txt | 1 +
1 file changed, 1 insertion(+)
create mode 100644 Tugas-Js.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 292 bytes | 292.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/keqi000/belajarGIT.git
5f0cef5..4f0dfcd main -> main

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git branch Tugas-midProject

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-midProject)
$ touch Tugas-MidProject.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-midProject)
$ git commit -m "menambah file tugas-midproject.txt"
[Tugas-midProject 119d9c1] menambah file tugas-midproject.txt
1 file changed, 1 insertion(+)
create mode 100644 Tugas-MidProject.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-midProject)
$ git chechout main
git: 'chechout' is not a git command. See 'git --help'.

The most similar command is
checkout

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git merge Tugas-midProject
Updating 4f0dfcd..119d9c1
Fast-forward
Tugas-MidProject.txt | 1 +
1 file changed, 1 insertion(+)
create mode 100644 Tugas-MidProject.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 306.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/keqi000/belajarGIT.git
4f0dfcd..119d9c1 main -> main

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git branch Tugas-php

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-php)
$ touch Tugas-Php.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-php)
$ git commit -m "menambah file tugas-php.txt"
[Tugas-php a25ad63] menambah file tugas-php.txt
1 file changed, 1 insertion(+)
create mode 100644 Tugas-Php.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git merge Tugas-php
Updating 119d9c1..a25ad63
Fast-forward
Tugas-Php.txt | 1 +
1 file changed, 1 insertion(+)
create mode 100644 Tugas-Php.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 295 bytes | 295.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/keqi000/belajarGIT.git
119d9c1..a25ad63 main -> main

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git branch Tugas-finalProject

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-finalProject)
$ git commit -m "menambah file tugas-project.txt"
[Tugas-finalProject fa1334f] menambah file tugas-project.txt
1 file changed, 1 insertion(+)
create mode 100644 Tugas-FinalProject.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git merge Tugas-finalProject
Updating a25ad63..fa1334f
Fast-forward
Tugas-FinalProject.txt | 1 +
1 file changed, 1 insertion(+)
create mode 100644 Tugas-FinalProject.txt

asus@LAPTOP-FJNNHFKT MINGW64 /d/Kiki/Kuliah Kiki/SEMESTER 4/PEMROGRAMAN WEB/TUGAS/Tugas 1 git/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 310 bytes | 310.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/keqi000/belajarGIT.git
a25ad63..fa1334f main -> main
