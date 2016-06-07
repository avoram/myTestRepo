1) Add files to git - git add . 
2) check the status - git status
3) commit - git commit -m "Commit Message"
4) Flow : working copy > staging area > repository
5) Show the changes - git diff
6) Remove/delete file :- git rm index.html
7) Rename files - git mv index.html home.html
8) Moving to another folder - git mv index.html view/home.html
9) Undo Changes : git checkout -- README.txt
10)Bring back file from staging area to working copy - git reset HEAD index.html
11)Getting older versions : 
	a) See the log - git log
	b) Removing wrong commit : git checkout commit-version --README.txt
	eg: git checkout 73edfg --README.txt
12) Directly pushing from working copy to repository without staging:
	Normal flow : a) Add file to statging area(git add .) 
				  b) Commit the changes - git commit -m 'changes commited'
	
	Direct changes : Add+commit --> git commit -am 'Skipping stagging step and directly commit working copy > repository'	

13)Adding files to Github : 

	a)set the nick name and connection to gihub project : git remote add myTestRepo https://github.com/avoram/myTestRepo.git
	b)git remote -> myTestRepo
	c)Pushing changes -> git push -u myTestRepo
	d)This will add the files to Github.
	
14)git ignore : add .gitignore file and mention all the extension and file which need not be watched by git.
15)Using Github desktop : Make a clone of the project and sync the changes.
16)Create a branch and modify the files and then make the pull request to merge in master branch.

	