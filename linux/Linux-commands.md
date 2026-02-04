# What I did 

- Watched a [Youtube video] (https://www.youtube.com/watch?v=lCq4mYQL0WY) explaining fundemental linux commands that are useful for DevOps to reinforce and expand my knowledge.

- Learned there is some crossover between what I've already been using in terminal to manage git resources 
as well as new/ more advanced ways of using commands 


# Next steps

- Put this knowledge into practice by deploying a linux server on AWS, connecting to it via SSH and installing some packages or hosting a basic project on it.


# Commands 




 ## file exploration  

ls - lists directories/files 

mkdir - makes folder

cd - change directory 

touch - creates file 

nano -  Text editor/ input text into a file ; can also create text file : Ctrl+0 save Ctrl+X to exit 

cat - reads output of text file 

rm - remove file 

pwd - present working directory 

create multiple files . touch 1.txt 2.txt  

rm * - delete everything in the directiory 

ls - l  lists files and their type 

cd .. - go back to previous diectory

rmdir - remove directory if empty

&& can seperate commands to do in one line - EG mkdir test && cd test 

man - manual on command eg ; man rm fetches information about the command used for removing files 

cp - copy file (needs directory after eg; cd 1.txt test/)

mv - move a file (same syntax as cp)

mv 1.txt new.txt - renames the file from 1 to new 

~ - home directory 

~ a - can list files starting with a in the home directory 
history - history of commands
## Installation


sudo - superuser, root account admin priveleges 

apt- installation within ubuntu can vary for different linux distros 

amazon linux based on fedora - yum package instead 

sudo apt install - installs package 

sudo apt update - refreshes database to check for updates 

sudo apt upgrade - insalls newer versions 

usage : sudo apt update && sudo apt upgrade - checks for updates and installs

sudo apt purge - removes package 


## SSH 

ssh -i key.pem username@ipadress 

exit - closes ssh session 

# Network commands 

 ping url  - check if website is responding 
 
nslookup url  -  gives information about the domain

curl url  - get contents of website in html 

wget url - download content 



## misc 
whoami - what user 

sudo su - changes you to root user 

which - shows where file is installed 

vi - enter file within terminal alternative to nano , need to type I first 
 to exit press esc key  qa! exit without saving , wq exit and save 

 # errors 
 
- Forgot to cd into file when committing this to github and ended up running git in my home directory, making all my personal files into a git repository

fix : rm -rf .git in the location 

- Didnt save file on vscode so committed blank text 

