*Disclaimer: these key terms are for Mac OS users. Other operating systems may use slightly different terms.*
> This folder will be updated regularly whenever relevant terms are introduced. 

# Terminal Key Terms 
> Terminal is a command line system that can help you quickly take control of your operating system and make changes.
```
cd -> change directory (moves you into a folder)
cd - -> goes back one step 
ls -> show files (list)
ls -a -> shows hidden files (only on terminal)
clear -> clears terminal
history -> shows most recent history of commands
open -> opens selected file
mkdir -> makes a folder in chosen location
rmdir -> removes the folder
touch -> creates file with selected name
rm -> removes selected file
code . -> opens file in visual studio code (if doesn't work, use cmd+shift+p in VSC and select 'path')
```
# Git Key Terms 
> Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows
```
command + j -> opens terminal in visual studio code
```

These initial commands will help set up your first repository on [Github](https://github.com/)

```
git init -> creates a repository 
git add [insert file name here] -> adds your files to the staging area
git commit -m "text here" -> adds a message to your commit i.e. labels your changes
git remote add origin [github repo link] -> this adds the repo you will be pushing to


git branch -m main -> renames branch you are currently on to 'main'
git branch -m <oldname> <newname> -> renames selected branch to a new name 
git push origin -u <newname> -> pushes your local branch and resets upstream branch
```