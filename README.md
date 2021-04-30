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

	rm:

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


	cp:

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


	mv:

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

	diff:

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ diff test1 test2
Only in test1: test1.1
Only in test1: test1.2
Only in test2: test2.1


	cat:




	-find files, folders and inside files:

	grep:

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


	cat:



	echo:



	-create and edit text files:

	nano: This command will create a file and incase it has already been created will enter to the file to edit it

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam (master)
$ nano README.md


	vim:



	touch:



	cat + ">":

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ cat test1.1 > "This still a test"

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ cat test1.1
This is a test

Usuario@DESKTOP-VA1PJA4 MINGW64 ~/Desktop/Extemporary_ Exam/test1 (master)
$ ls
'This still a test'   test1.1   test1.2/

	
	-get the state of the computer:

	history:



	top:



	WhoamI:



2.-The git / github with examples:

	-the intial configuration
	
	-starting a project from zero or clonning an existing repository

	-basic workflow commands to stage and commit

	-push to a remote repository

	-branches: create, delete, save/commit and merge

	-gitflow

	
