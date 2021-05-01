# Extemporary_Exam
1.- The commant line

	-create and delete directories:

	cd:This command will allow you to move to directories named also if we writte cd.. we to back once and if we wirtte cd ../.. we go back twice

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ ls
README.md  test1/  test2/

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ cd test1

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ pwd
/c/Users/Usuario/Desktop/Extemporary_ Exam/test1

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ cd ..

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ pwd
/c/Users/Usuario/Desktop/Extemporary_ Exam

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ cd test1

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ cd ../..

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop
$


	mkdir: The command will make a directory


Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ mkdir Part_ome

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ mkdir Part_two

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ ls
Part_one/  Part_two/

	rm: This command will remove a file that you have

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ ls
README.md  test1/  test2/

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ cd test1

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ ls

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ nano test1.1

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ rm test1.1

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ ls

	
	rmdir: The command will remove a directory

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ rmdir Part_ome

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ ls
Part_two/


	cp: This will copy the content of a file and put it in another file with another name

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ nano test1.1

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ cp test1.1 test2

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ ls
test1.1  test2

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ cat test1.1
This is a test

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ cat test2
This is a test


	mv: You can mive files with this as in the example the file test2 is moved to the directory test1.2 

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ ls
test1.1  test2

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ mkdir test1.2

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ ls
test1.1  test1.2/  test2

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ mv test2 test1.2

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ ls
test1.1  test1.2/

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ cd test1.2

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1/test1.2 (master)
$ ls
test2


	-navigate:

	cd: This command will allow you to move to directories named also if we writte cd.. we to back once and if we wirtte cd ../.. we go back twice

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ ls
README.md  test1/  test2/

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ cd test1

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ pwd
/c/Users/Usuario/Desktop/Extemporary_ Exam/test1

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ cd ..

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ pwd
/c/Users/Usuario/Desktop/Extemporary_ Exam

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ cd test1

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ cd ../..

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop
$


	pwd: This will show you the directory that you are

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ pwd
/c/Users/Usuario/Desktop/Extemporary_ Exam


	-compare:

	diff: This will show you the differences between your directories

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ diff test1 test2
Only in test1: test1.1
Only in test1: test1.2
Only in test2: test2.1


	-find files, folders and inside files:

	grep: This command will look in you computer files to find the files with the name you wrote as in the example is git grep test

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ git grep test
README.md:README.md  test1/  test2/
README.md:$ cd test1
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:/c/Users/Usuario/Desktop/Extemporary_ Exam/test1
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:$ cd test1
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:README.md  test1/  test2/
README.md:$ cd test1
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:$ nano test1.1
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:$ rm test1.1
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:$ nano test1.1
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:$ cp test1.1 test2
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:test1.1  test2
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:$ cat test1.1
README.md:This is a test
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:$ cat test2
README.md:This is a test
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:test1.1  test2
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:$ mkdir test1.2
README.md:Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
README.md:test1.1  test1.2/  test2
:

	-create and edit text files:

	nano: This command will create a file and incase it has already been created will enter to the file to edit it

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ nano README.md


	vim: This will create a fille but the editor of the text will be vim insted of nano in case you want to go out of vim you need to write :wq

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ vim test4

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ cat test4
Hi


	git touch: This will create archives as we see I create test.txt

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ touch test.txt

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ ls
README.md  test.txt  test1/  test2/  test3/  test4


	cat + ">": This will let you see the content of a file and at the same time add a new file

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ cat test1.1 > "This still a test"

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ cat test1.1
This is a test

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ ls
'This still a test'   test1.1   test1.2/

	
	-get the state of the computer:

	history: This will  allow you to see the commands that you have written

  507  ls
  508  echo "test2"
  509  ls
  510  pwd
  511  cd ..
  512  nano README.md
  513  nano README.md
  514  ls
  515  cd test1
  516  cat test1
  517  ls
  518  cat test1.1
  519  cd ..
  520  nano README.md
  521  cd test1
  522  cat test1.1 > This still a test
  523  cat test1.1 > "This still a test"
  524  cat test1.1
  525  ls
  526  rm This
  527  ls
  528  cd ..
  529  nano README.md
  530  history


	WhoamI: This will show you the name of the computer that print this comment

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ whoami
Usuario


2.-The git / github with examples:

	-the intial configuration: This commands will help you to put you name and the email you want people to see whenever you make and change and commit.
	
	$ git config --global user.name "Antoniowtd"
	$ git config --global user.email antonio.rn@outlook.com

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
      user.name=Antoniowtd
      user.email=antonio.rn@outlook.com
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/Antoniowtd/Extemporary_Exam.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.master.remote=origin
branch.master.merge=refs/heads/master


	-starting a project from zero or clonning an existing repository: 

	git init will indicate that you just started a project

	git clone "URL" will copy the repository of the url

echo "# Hola" >> README.md
git init
git add README.md
git commit -m "first commit"

in case you clone:

git clone  https://github.com/Antoniowtd/Git-and-GitHub-Markdown.git

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop
$ git clone https://github.com/Antoniowtd/Git-and-GitHub-Markdown.git
Cloning into 'Git-and-GitHub-Markdown'...
remote: Enumerating objects: 25, done.
remote: Counting objects: 100% (25/25), done.
remote: Compressing objects: 100% (19/19), done.
remote: Total 25 (delta 6), reused 22 (delta 3), pack-reused 0
Receiving objects: 100% (25/25), 4.68 KiB | 4.68 MiB/s, done.
Resolving deltas: 100% (6/6), done.

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop
$ ls
 Antonio/                    'League of Legends.lnk'*
'Apex Legends.url'           'Lively Wallpaper.lnk'*
 Atom.lnk*                   'Microsoft Teams.lnk'*
 BPM/                         OP.GG.lnk*
 Blitz.lnk*                  'Python 3.9 (64-bit) (2).lnk'*
'Cisco Webex Meetings.lnk'*   Spotify.lnk*
 Dev-C++.lnk*                 TLauncher.lnk*
 Discord.lnk*                 desktop.ini
 Escuela/                     khjvol/
'Extemporary_ Exam'/          sdfaerg.mcworld
 	#Git-and-GitHub-Markdown/

	As we see in the last one we found the file cloned



	-basic workflow commands to stage and commit

	git status: you will use git status in case you want to see the files if they are being follow or not

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   test3/test3.1

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

	git add:In case the file is not being follow you added to the stage

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ git add *
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

	git commit -m "The comment of the commit": in case everything is on the stage area you commit and place a commet with the changes

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ git commit -m "Commit to explain the commands to stage and commit"
[master 4aa7203] Commit to explain the commands to stage and commit
 2 files changed, 37 insertions(+), 4 deletions(-)
 create mode 100644 test3/test3.1

	-push to a remote repository

	git push -u origin master: This comment will Upload the remote repository

echo "# Hola" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Antoniowtd/Hola.git
git push -u origin main



	-branches: create, delete, save/commit and merge


	create:
	git checkout -b "Name": With this you will create and move to a new branch thta you create

$ git checkout -b SecondBranch
Switched to a new branch "Second Branch"

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ git branch
* master

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ git checkout -b SecondBranch
Switched to a new branch 'SecondBranch'

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (SecondBranch)
$ git branch
* SecondBranch
  master


	Delete:
	git branch -d "Name": With this you will delete a branch named

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ git branch -d SecondBranch
Deleted branch SecondBranch (was c498428).

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ git branch
* master


	Save/Commit:
	git stash: This will upload you chages that the branch that you are in have


	Merge:
	git merge: This will combine your two branches


	-gitflow

	gitflow: This will create a branch created around a project.

first you clone a repository:

git clone:https://github.com/Antoniowtd/Hola.git

then you create a branch:

git cheackout -b develop master

Then you create a branch in the remote repository:

git push --set-upstream origin develop

and you initializate gitflow:

Git flow init
