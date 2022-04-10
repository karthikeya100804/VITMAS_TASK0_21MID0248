# VITMAS_TASK0_21MID0248
git help
Take help from github help section for different commands and other errors 

git config
To set the basic configurations on github like your name and email
 
git config –-global user.name “Karthikeya Kommuru”
Sets configuration values for your user name on git  

git config –-global user.emaiL kommurukarthikeya66@gmail.com
Sets configuration values for your user email on git

mkdir store
Create a directory if not created initially

cd store
To go inside the directory and work upon its contents

git init
To create a local git repository for us in our store folder.This will help to manage the git commands for that particular repository. 

git status
To see whats changed since last commit.It shows all the files that have been added and modified and ready to be commmitted and files which are untracked 

git add Readme.txt
To add a file Readme.txt to the staging area to track its changes

git commit -m “Created a Readme.txt”
To commit our changes(taking a snapshot) and providing a message to remember for future reference

git log
To check the history of commits for our reference

git add
To add a specific list of files to staging area

git add --all
To add all files of current directory to staging area

git add *.txt
To add all text files of the current directory to staging area

git add docs/*.txt
To add all text files of a particular directory to staging area

git add docs/
To add all files in a particular directory to staging area

git add “*.txt”
To add text files of entire project to staging area

git commit -a -m “Readme.md”
To add any of our tracked files to staging area and commit them by providing a message to remember

git reset –soft HEAD^
To undo last commit and bring file to staging area

git reset –hard HEAD^
To undo last commit and remove file from the staging area

git reset –hard HEAD^^
To undo last 2 commits and all changes

git remote add origin https://github.com/karthikeya100804/VITMAS_TASK0_21MID0248.git
This commands make a bookmark which signifies that this particular remote refers to this URL. 
This remote will be used to pull any content from the directory and push our local content to the global server

git clone https://github.com/karthikeya100804/VITMAS_TASK0_21MID0248.git
To clone or make a local copy of the global repository in your system 
