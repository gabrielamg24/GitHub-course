# SST
Program version control on local computer  creates repository with all files 
Internet hosting service for git repositories, work on multiple computers, working from any computer connecting to the internet

###GitHub
1.	Create github project
2.	The first time clone the repository into the computer, all the other times “git pull” is used to copy files into computer
3.	Once you have edited your file in the local computer then it is committed into github again 
4.	Forking: make a copy of a repository, the pull request can be rejected by the creator of the file 
5.	Branching: 
6.	Github 

###Ask to be a collaborator
1.	Go to the page of the project
2.	Go to issues tab
3.	New issue: can I be a collaborator? 

###Add a collaborator
1.	Within the repository
2.	Go to Settings
3.	Go to collaborators
4.	Add a person by username or e-mail 

###Be a friend
1.	Go to github principal page
2.	Search the username
3.	follow

###Create a to-do list 
1.	Go to gist.github.com
2.	Create new list
3.	Use code
		#To Do 
- [ ] project
- [x] groceries
- [ ] hw
- [x] clean

###Fork a repository
1.	Go to the person’s account
2.	Top right  fork
3.	Takes a couple of seconds
4.	Go to the fork
5.	Copy url 
6.	Git clone the url in your terminal

###Create a license 
1.	Go to the repository
2.	Create a new file
3.	Name it license.txt
4.	Choose a license: GNU GENERAL PUBLIC LICENSE
5.	Commit file into the master branch
![Alt text](https://github.com/gabrielamg24/GitHub-course/blob/images/license.png)

 
###Create a Gitignore
1.	Go to the repository
2.	Create a new file
3.	Name it touch.gitignore
4.	Copy code from https://gist.github.com/octocat/9257657
5.	Commit file into the master branch

###Starring projects
1.	Go to an account or find a project
2.	Click the little star

![Alt text](https://github.com/gabrielamg24/GitHub-course/blob/images/stars1.png)

###Adding an image to a .md
1.	Open the file 
2. 	copy the URL link of the image, either from the red or from within github 
3.	puting the image in () after the text: ![Alt text]

###How to use in Peregrine
1.Create account on github
2.create repository 
3.go onto terminal and onto peregrine 
>ssh f111552@peregrine.hpc.rug.nl
>module load git
>git clone https://github.com/gabrielamg24/SST.git
>cd SST
>git add --all :/
>git config --global user.mail "gabrielamg24@gmail.com"
>git config --global user.name "gabrielamg24"
>git commit -m "MESSAGE"
>git push
>git pull
>SST git status
-When you go to github and create a new file then you go back to your terminal and 
>git commit -m "MESSAGE"
>git pull
-On the github webpage you request to be a collaborator, once you have received the mail and accepted the invitation then you can go to your terminal and clone it, then pull it, then edit, then push it. 
>git clone https://github.com/Lumphie/Fairytale_test.git
>cd Fairytale_test
>git pull
-Edit the files from your computer
>git push 
-On github create a license https://help.github.com/articles/adding-a-license-to-a-repository/ and a gitignore https://help.github.com/articles/ignoring-files/ , these were created in a branch and not in the master branch, soooo go to terminal 
>git pull
>git checkout  gabrielamg24-patch-1
>ll (to check files are there) 
>git checkout master
>ll
>git merge gabrielamg24-patch-1 (from the master branch you ask to merge with the branch with the files so they’re copied into master)
>ll 

