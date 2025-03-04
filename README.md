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
nobia@LENOVO MINGW64 ~
$ cd Documents

nobia@LENOVO MINGW64 ~/Documents
$ git clone https://github.com/NobianaLie/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

nobia@LENOVO MINGW64 ~/Documents
$ cd belajarGIT

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-git

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ notepad Tugas-git.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-git.txt"
[Tugas-git 85bb062] Menambahkan Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-git
Updating 507db25..85bb062
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 314 bytes | 314.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/NobianaLie/belajarGIT.git
   507db25..85bb062  main -> main

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-html

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ touch Tugas-git.html

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ notepad Tugas-html.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-html.txt"
[Tugas-html 59abee1] Menambahkan Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-html
Updating 85bb062..59abee1
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 345 bytes | 172.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/NobianaLie/belajarGIT.git
   85bb062..59abee1  main -> main

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-css

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ notepad Tugas-css.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-css.txt"
[Tugas-css b9c82b3] Menambahkan Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-css
Updating 59abee1..b9c82b3
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 374 bytes | 187.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/NobianaLie/belajarGIT.git
   59abee1..b9c82b3  main -> main

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-js

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ notepad Tugas-js.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git commit -m "menambahkan Tugas-js.txt"
[Tugas-js 04c0ca6] menambahkan Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-js
Updating b9c82b3..04c0ca6
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 305 bytes | 61.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/NobianaLie/belajarGIT.git
   b9c82b3..04c0ca6  main -> main

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-midProject

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ notepad Tugas-midProject.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-midProject.txt"
[Tugas-midProject 962dfaa] Menambahkan Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-midProject
Updating 04c0ca6..962dfaa
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 323 bytes | 35.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/NobianaLie/belajarGIT.git
   04c0ca6..962dfaa  main -> main

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-php

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ notepad Tugas-php.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-php.txt"
[Tugas-php 71f98e8] Menambahkan Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-php
Updating 962dfaa..71f98e8
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 308 bytes | 154.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/NobianaLie/belajarGIT.git
   962dfaa..71f98e8  main -> main

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git branch Tugas-finalProject

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ notepad Tugas-finalProject.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-finalProject.txt"
[Tugas-finalProject 84e81c2] Menambahkan Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git merge Tugas-finalproject
Updating 71f98e8..84e81c2
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

nobia@LENOVO MINGW64 ~/Documents/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 314 bytes | 62.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/NobianaLie/belajarGIT.git
   71f98e8..84e81c2  main -> main
