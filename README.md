# GitHub Tutorial

_by Hector Marin_

---
## Git vs. GitHub
* Git is a code language and use it for github
* Github is a website to store code and work

---

## Initial Setup
* sign into github or create a new github account
* click on profile in the top right
* go to settings
* go to SSH and GPG keys tab


---
## Repository Setup
* go to your github profile
* go to "Repositories"
* go to new
* create a new repository
* Congratulations, you have made a repository


---
## Workflow & Commands
1. ```cd [name]``` move up into a folder
2. ```mkdir [name]``` make a directory
3. ```touch.filename```make a file
4. ```rmdir [name]```remove an empty directory
5. ```rm rf dir [name]```removes a directory full or not with force
6. ```mv [name] [NewName]```rename a file to something else ,You can also move a file to an existing folder with the same command.
7. ```git push``` sends the changes to github
8. ```git commit -m"message"``` takes a "snapshot" of the code
9. ```git add .``` adds all files
10. ```git status``` checks to see if a file has been added:red means no, green means yes.
11. ```ls``` lists the directories you went into
12. ``` ` ``` That is a tilda, it can bring you back to the root
13. ```cd ..``` moves up a folder from where you entered

---
## Rolling Back Changes
* ```git checkout -- filename``` : undoes a edit
* ```git reset HEAD filename``` : undoes add
* ```git reset --soft HEAD~1``` : undoes a commit
* ```git reset HEAD~1``` : undoes the last commit and unstages the file
* ```git reset –hard HEAD~``` : undoes a pushed commit
* ```git reset --hard HEAD~1``` : undoes a commit, unstages the file and deletes all the changes
