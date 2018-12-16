
# Most UseFull Git Commands - A Compiled version

***GIT*** - **Git is mostly widely used Open-source Distributed version Control system. Git is developed by [Linus Torvalds](https://en.wikipedia.org/wiki/Linus_Torvalds)**. Today,developers around the world are migrating on Git to mange their 
source code. Git as a version control system not only used to manage largescale project but can also be used by individuals.

Git comes with both Public and Private repository flavours. Private version of it is paid.

Git is vast and wide range of commands and tools available to manage repositories. Not all options of Git are needed 
for all developers. Let's see most widely used Git options.

**Initializing Git Repository**   
*```git init```*

**Adding remote Git Repository to existing git init folder**
* ```git remote add origin https://github.com/harshmaheshwari001/<repo_name>```*

**Cloning a Git Repository**   
*```git clone https://github.com/harshmaheshwari001/data-structure.git```*

**Adding file and folders for git Tracking**    
*```git add README.md```*  
*```git add <folder_path>/```*  

**Commit to local git repository**
*```git commit -m 'commit_message'```*  

**Set Upsteam origin/branch Branch**  
*```git branch --set-upstream-to=origin/master```*  

**Push with set Upstream origin branch**  
*```git push --set-upstream origin master```*

**Check currrent branch & Upsteam remote connected to**  
*```git branch -vv```*   

**Check git log (Check git commit history sorted by lastest)**  
*```git log```* 

**Give you git local repository status information**  
*```git status```* 
    - Gives information like untracked file & branch information    

**Git reset will match local branch with remote origin**   
*```git reset --hard origin/master```*  
    - It will set your local branch to match the representation of the remote just pulled down  
    
**Delete local branch**    
*```git branch -d hotfix```*    

[References](#reference_link)
* https://en.wikipedia.org/wiki/Linus_Torvalds 
* https://dzone.com/refcardz/getting-started-git 
* https://kbroman.org/github_tutorial/pages/init.html
