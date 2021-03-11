# Soru-1:
Bu haftaki ödevinizin cevabını git projesi kullanarak cevaplayınız. Ödev tamamlanana kadar en az 3 commit yapınız. Projenizi uzak repo olarak github'a entegre ediniz.

On browser I create a github project  :bash_docker_practice

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler
$ git init
Initialized empty Git repository in D:/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler/.git/

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (master)
$ git config --global user.name "Berkan Acar"

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (master)
$ git config --global user.email "berkanacar@gmail.com"

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (master)
$ git remote add origin https://github.com/berkarcan/bash_docker_practice.git

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (master)
$ git add .

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   02_bashscript_homework_cozum.md
        new file:   03_docker_homework - cozum.md

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (master)
$ git commit -m "Practice first findings"
[master (root-commit) f7b5e5a] Practice first findings
 2 files changed, 73 insertions(+)
 create mode 100644 02_bashscript_homework_cozum.md
 create mode 100644 03_docker_homework - cozum.md

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (master)
$ git branch -M main

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.82 KiB | 1.82 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/berkarcan/bash_docker_practice.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (main)
$ git add .

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (main)
$ git commit -m "01_git_homework - Cozum.md"

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (main)
$ git push -u origin main

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (main)
$ git add .

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (main)
$ git commit -m "01_git_homework - Cozum.md firs changes"

berka@LAPTOP-G7STU4QJ MINGW64 /d/ders_notları/6. Hafta/Ödevler/bash_docker_cozumler (main)
$ git push -u origin main
