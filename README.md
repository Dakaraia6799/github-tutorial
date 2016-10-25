# GitHub Tutorial

_by Dakarai Arnold_

---
## Git vs. GitHub
#### Git: 
Is a distributed version control system and is responsible for keeping track of all changes to content it also allows you to share content with others.  
#### GitHub:  
Is a git repository hosting service, it provides a web-based interface and other things like access control and several other collaboration features.  
#### Difference:  
The difference between Git and Github is that Git takes snapshots of code however, you cannot use Github without git. GitHub stores save code in the website also known as the "clouds".




---
## Initial Setup  
In order for you to setup a accout you do the following:  
1) go to [Github](github.com) and click the octocat on the top right  
2) make the username you desire  
3) create a password  
4) if a bubble pops up saying it is wrong just ignore it  
5) make a free acount   
6) press finish sign-up and go to [c9.io](c9.io)  
7) click the octocat in the top right corner  
8) press connected services to connect it to your github  




---
## Repository Setup  
1) create a new direcotry  
2) cd into that new direcotry  
3) initialize git in this new directory  
4) use git add to add your directory to the "stage"  
5) then commit your file so htat its uploaded to the repository  
6) finally you would use git push so it is uploaded to the github and is abled to be pulled down   




---
## Workflow & Commands
#### Git status:
This command shows you the previous changes that was made to your code.  

#### Git add:
Doing this command will add whatevers in your working direcotry to  the "stage" so it is ready to be commited.

#### Git commit:  
This command uploads your code and any changes to the code that was on the "stage" to the local repository.

#### Git push: 
Doing this command will upload any commits you have recently uploaded to the local repository to the remote.  

## Error handling:  
A error most students do is forget to initialize git inside of the workspace instead of the direcotry they created. a way to fix this is uninitializing git by doing the command rm -rf .git then cd into the direcotry you want then initialize git