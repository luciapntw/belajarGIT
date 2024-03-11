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
...
lucia@LuciaPantow MINGW64 ~
$ git config --global user.email "pantowlucia@gmail.com"

lucia@LuciaPantow MINGW64 ~
$ git init
Initialized empty Git repository in C:/Users/lucia/.git/

lucia@LuciaPantow MINGW64 ~ (master)
$ cd Deskop
bash: cd: Deskop: No such file or directory

lucia@LuciaPantow MINGW64 ~ (master)
$ cd Deskop
bash: cd: Deskop: No such file or directory

lucia@LuciaPantow MINGW64 ~ (master)
$ cd desktop

lucia@LuciaPantow MINGW64 ~/desktop (master)
$ git clone https://luciapntw/belajarGIT.git^C

lucia@LuciaPantow MINGW64 ~/desktop (master)
$

lucia@LuciaPantow MINGW64 ~/desktop (master)
$ git clone https://github.com/luciapntw/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

lucia@LuciaPantow MINGW64 ~/desktop (master)
$ cd BelajarGIT

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch
* main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ ^C

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch Tugas-html

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch
  Tugas-html
* main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git checkout -b Tugas-html
fatal: a branch named 'Tugas-html' already exists

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ touch Tugas-html.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ git add Tugas-html.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html c83a8d8] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ ^C

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ ^C

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ cd git
bash: cd: git: No such file or directory

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ cd -
/c/Users/lucia/desktop

lucia@LuciaPantow MINGW64 ~/desktop (master)
$ cd Git
bash: cd: Git: No such file or directory

lucia@LuciaPantow MINGW64 ~/desktop (master)
$ ls
belajarGIT/

lucia@LuciaPantow MINGW64 ~/desktop (master)
$ git add Tugas-html.txt
fatal: pathspec 'Tugas-html.txt' did not match any files

lucia@LuciaPantow MINGW64 ~/desktop (master)
$ git add Tugas-html.txt
fatal: pathspec 'Tugas-html.txt' did not match any files

lucia@LuciaPantow MINGW64 ~/desktop (master)
$ cd BelajarGIT

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ git add Tugas-html.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
On branch Tugas-html
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-html.txt.txt

nothing added to commit but untracked files present (use "git add" to track)

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ git add Tugas-html.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
On branch Tugas-html
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-html.txt.txt

nothing added to commit but untracked files present (use "git add" to track)

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
On branch Tugas-html
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-html.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-html.txt.txt

no changes added to commit (use "git add" and/or "git commit -a")

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ git add Tugas-html.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
[Tugas-html cdddae0] Menambahkan perubahan pada Tugas-html.txt
 1 file changed, 1 insertion(+)

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ git add Tugas-html.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
On branch Tugas-html
nothing to commit, working tree clean

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git merge Tugas-html

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git push origin main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git push origin main
Everything up-to-date

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git push origin Tugas-html
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 579 bytes | 579.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-html' on GitHub by visiting:
remote:      https://github.com/luciapntw/belajarGIT/pull/new/Tugas-html
remote:
To https://github.com/luciapntw/belajarGIT.git
 * [new branch]      Tugas-html -> Tugas-html

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch
  Tugas-html
* main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch Tugas-git

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git checkout -b Tugas-git
fatal: a branch named 'Tugas-git' already exists

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ touch Tugas-git.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git add Tugas-git.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git commit -m "Menambahkan file Tugas-git.txt"
[main 663cdfd] Menambahkan file Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git add Tugas-git.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-git.txt"
[main d16e780] Menambahkan perubahan pada Tugas-git.txt
 1 file changed, 1 insertion(+)

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git merge Tugas-git
Already up to date.

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 577 bytes | 577.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/luciapntw/belajarGIT.git
   d2874ba..d16e780  main -> main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git push origin Tugas-git
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-git' on GitHub by visiting:
remote:      https://github.com/luciapntw/belajarGIT/pull/new/Tugas-git
remote:
To https://github.com/luciapntw/belajarGIT.git
 * [new branch]      Tugas-git -> Tugas-git

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch Tugas-css

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git checkout -b Tugas-css
fatal: a branch named 'Tugas-css' already exists

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ touch Tugas-css.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git add Tugas-css.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git commit -m "Menambahkan file Tugas-css.txt"
[main 277e4e4] Menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git add Tugas-css.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-css.txt"
[main 6222057] Menambahkan perubahan pada Tugas-css.txt
 1 file changed, 1 insertion(+)

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git merge Tugas-css
Already up to date.

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 630 bytes | 630.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/luciapntw/belajarGIT.git
   d16e780..6222057  main -> main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git push origin Tugas-css
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-css' on GitHub by visiting:
remote:      https://github.com/luciapntw/belajarGIT/pull/new/Tugas-css
remote:
To https://github.com/luciapntw/belajarGIT.git
 * [new branch]      Tugas-css -> Tugas-css

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch Tugas-js

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git checkout -b Tugas-js
fatal: a branch named 'Tugas-js' already exists

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ touch Tugas-js.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git add Tugas-js.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git commit -m "Menambahkan file Tugas-js.txt"
[main a0f782b] Menambahkan file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git add Tugas-js.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-js.txt"
[main a23918a] Menambahkan perubahan pada Tugas-js.txt
 1 file changed, 1 insertion(+)

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git merge Tugas-js
Already up to date.

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 524 bytes | 524.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/luciapntw/belajarGIT.git
   6222057..a23918a  main -> main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git push origin Tugas-js
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Tugas-js' on GitHub by visiting:
remote:      https://github.com/luciapntw/belajarGIT/pull/new/Tugas-js
remote:
To https://github.com/luciapntw/belajarGIT.git
 * [new branch]      Tugas-js -> Tugas-js

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch Tugas-midProject

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* main

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ touch Tugas-midProject.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git add Tugas-midProject.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[main da6fa47] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git add commit -m "Menambahkan perubahan pada Tugas-midProject.txt"
error: unknown switch `m'
usage: git add [<options>] [--] <pathspec>...

    -n, --[no-]dry-run    dry run
    -v, --[no-]verbose    be verbose

    -i, --[no-]interactive
                          interactive picking
    -p, --[no-]patch      select hunks interactively
    -e, --[no-]edit       edit current diff and apply
    -f, --[no-]force      allow adding otherwise ignored files
    -u, --[no-]update     update tracked files
    --[no-]renormalize    renormalize EOL of tracked files (implies -u)
    -N, --[no-]intent-to-add
                          record only the fact that the path will be added later
    -A, --[no-]all        add changes from all tracked and untracked files
    --[no-]ignore-removal ignore paths removed in the working tree (same as --no-all)
    --[no-]refresh        don't add, only refresh the index
    --[no-]ignore-errors  just skip files which cannot be added because of errors
    --[no-]ignore-missing check if - even missing - files are ignored in dry run
    --[no-]sparse         allow updating entries outside of the sparse-checkout cone
    --[no-]chmod (+|-)x   override the executable bit of the listed files
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separated with NUL character


lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-midProject.txt"
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-midProject.txt

no changes added to commit (use "git add" and/or "git commit -a")

lucia@LuciaPantow MINGW64 ~/desktop/BelajarGIT (main)
$ git commit -m "Menambahkan perubahan pada Tugas-midProject.txt"
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-midProject.txt

no changes added to commit (use "git add" and/or "git commit -a")
