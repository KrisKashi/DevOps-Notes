Git/Github Learning summary 

# What I did 
- Learned Git runs locally whereas Github Hosts online 
-  Created a Github repo and cloned it using git
- Setup SSH authentication to link my Github account 
-  Created folders and files using terminal
-  Moved over to edit in VScode 
- Committed + Pushed to github 


# Commands 

GIT
- Git clone - download repository locally
- Git status - File changes 
- Git commit/add/push -  Upload changes

Terminal
- pwd - Where am I?
- cd - change directory /folder
- ls - list files 
- mkdir - makes folders
- touch - creates files 
  - ssh-keygen -t ed25519 -C "email" – generate SSH key
  - ssh-add ~/.ssh/id_ed25519 – load SSH key into agent
  - ssh -T git@github.com = verify SSH to github access 

# issues
- intiial error did not have a SSH key setup locally
    fix: Setup ssh key and add to agent 

- couldnt see repo folder as didnt clone it 
      fix : use git clone to clone repo


# Lessons 

- SSH works system wide in vscode/terminal 
- SSH can be used instead of passwords 
- Git = local github = online 

