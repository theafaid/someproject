### Intro 

- version control management
- Github is hosting repositories service
- git --version
- cloning
- identifiying
	```
	git config --global user.name=""
	git config --global user.email=""
	git config user.name || user.email
	```
- Commit & pushing
	- it's like ftp but more secure 
	- git status
	- origin >> remote repository 
	- master >> current branch 
	- commit means >> take the new changes and record it 
	- git log 
	- git log --pretty=oneline
	- - git log --pretty=oneline -2''
	
	- Pulling changes
		- git pull >> show the changes 
		
	- Branching 
		- process creating a new pointer 
		- if you are happy >> Merge if you are not delete the branch or do what you  want 
		- ``` git branch ..```
		- ``` git branch -b ..```
		- ``` git checkout ...```
		- ``` git branch ```
		- ``` git merge from to ```
		- ``` git branch -d ..```
		- ``` git push origin --delete hello-test```
	
	- Git ignore 
	- ``` git ignore --help```


	## Pull requested 
	
	1) collaborators can add changes to the project with out validation 
	2) fork


	## Inhanced section 
	what if we want to inhance our featrures ??