# Test1Repository

althaf@alta MINGW64 ~
$ cd Desktop/

althaf@alta MINGW64 ~/Desktop
$ cd fruit/

althaf@alta MINGW64 ~/Desktop/fruit
$ echo "# Test1Repository" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/alta12/Test1Repository.git
git push -u origin main
Initialized empty Git repository in C:/Users/althaf/Desktop/fruit/.git/
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
[master (root-commit) 5835c14] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 227 bytes | 227.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/alta12/Test1Repository.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

althaf@alta MINGW64 ~/Desktop/fruit (main)
$ git add .

althaf@alta MINGW64 ~/Desktop/fruit (main)
$ git branch -M main

althaf@alta MINGW64 ~/Desktop/fruit (main)
$ git remote add origin https://github.com/alta12/Test1Repository.git
error: remote origin already exists.

althaf@alta MINGW64 ~/Desktop/fruit (main)
$ git push -u origin main
Everything up-to-date
branch 'main' set up to track 'origin/main'.

althaf@alta MINGW64 ~/Desktop/fruit (main)
$ git remote add origin https://github.com/alta12/Test1Repository.git
error: remote origin already exists.

althaf@alta MINGW64 ~/Desktop/fruit (main)
$ git push -u origin main
Everything up-to-date
branch 'main' set up to track 'origin/main'.

althaf@alta MINGW64 ~/Desktop/fruit (main)
$ git add .

althaf@alta MINGW64 ~/Desktop/fruit (main)
$ git commmit -m "second commit"
git: 'commmit' is not a git command. See 'git --help'.

The most similar command is
        commit

althaf@alta MINGW64 ~/Desktop/fruit (main)
$ git commit -m "second commit"
[main d16b0fc] second commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 sample/test1.txt
 create mode 100644 test2.txt

althaf@alta MINGW64 ~/Desktop/fruit (main)
$ git branch -M main

althaf@alta MINGW64 ~/Desktop/fruit (main)
$ git remote add origin https://github.com/alta12/Test1Repository.git
error: remote origin already exists.

althaf@alta MINGW64 ~/Desktop/fruit (main)
$ git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 353 bytes | 353.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/alta12/Test1Repository.git
   5835c14..d16b0fc  main -> main
branch 'main' set up to track 'origin/main'.

althaf@alta MINGW64 ~/Desktop/fruit (main)
$ ^C

althaf@alta MINGW64 ~/Desktop/fruit (main)
$
