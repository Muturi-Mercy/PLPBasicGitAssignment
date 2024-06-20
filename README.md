# PLPBasicGitAssignment

Administrator@DESKTOP-854KJI4 MINGW64 ~
$ cd OneDrive

Administrator@DESKTOP-854KJI4 MINGW64 ~/OneDrive
$ cd Desktop

Administrator@DESKTOP-854KJI4 MINGW64 ~/OneDrive/Desktop
$ cd PLPBasicGitAssignment

Administrator@DESKTOP-854KJI4 MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment
$ git init
Initialized empty Git repository in C:/Users/Administrator/OneDrive/Desktop/PLPBasicGitAssignment/.git/

Administrator@DESKTOP-854KJI4 MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (main)
$ git remote add origin https://github.com/Muturi-Mercy/PLPBasicGitAssignment.git

Administrator@DESKTOP-854KJI4 MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (main)
$ touch hello.txt

Administrator@DESKTOP-854KJI4 MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (main)
$ git add hello.txt

Administrator@DESKTOP-854KJI4 MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (main)
$ git commit -m "Add hello.txt with a greeting"
[main (root-commit) 8440c38] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt

Administrator@DESKTOP-854KJI4 MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (main)
$ git push -u origin main
To https://github.com/Muturi-Mercy/PLPBasicGitAssignment.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Muturi-Mercy/PLPBasicGitAssignment.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Administrator@DESKTOP-854KJI4 MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (main)
$ git fetch
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 870 bytes | 58.00 KiB/s, done.
From https://github.com/Muturi-Mercy/PLPBasicGitAssignment
 * [new branch]      main       -> origin/main

Administrator@DESKTOP-854KJI4 MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (main)
$ git merge origin/main
fatal: refusing to merge unrelated histories

Administrator@DESKTOP-854KJI4 MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (main)
$ git rebase origin/main
Successfully rebased and updated refs/heads/main.

Administrator@DESKTOP-854KJI4 MINGW64 ~/OneDrive/Desktop/PLPBasicGitAssignment (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 312 bytes | 312.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Muturi-Mercy/PLPBasicGitAssignment.git
   48ae6ee..229d26f  main -> main
branch 'main' set up to track 'origin/main'.

