1. git config --global user.name
syntax:git config --global user.name "Your Name"
purpose:sets the username globally for all repositories
![alt text](<Screenshot (1).png>)

2. git config --global user.email
syntax:git config --global user.email"your@email.com"
purpose: sets email globally for commit identification
![alt text](<Screenshot (1)-1.png>)
![alt text](<Screenshot (2).png>)
3. git config --list
syntax:git config --list
Purpose:
Displays all configured Git settings.
Example:
git config --list

![alt text](<Screenshot (3).png>)
4. git config --unset
Syntax:
git config --unset user.name
Purpose:
Removes a configuration value.
Example:
git config --unset user.name

![alt text](<Screenshot (4).png>)
5. git init
Syntax:
git init
Purpose:
Initializes a new Git repository.
Example:
git init
![alt text](<Screenshot (5).png>)
6. git clone
Syntax:
git clone <repository-url>
Purpose:
Creates a copy of a remote repository.
Example:
git clone https://github.com/username/project.git
![alt text](<Screenshot (6).png>)
7. git clone --branch
Syntax:
git clone --branch branch-name <repo-url>
Purpose:
Clones a specific branch.
Example:
git clone --branch develop https://github.com/username/project.git
![alt text](<Screenshot (7).png>)
8. git clone --depth
Syntax:
git clone --depth <number> <repo-url>
Purpose:
Performs shallow clone (latest commit only).
Example:
git clone --depth 1 https://github.com/username/project.git
![alt text](<Screenshot (8).png>)
9. git status
syntax:
git status
purpose:
Shows working directory status.
Example:
git status
![alt text](<Screenshot (9).png>)
 10. git log
syntax:git log
purpose:
Shows full commit history.
Example:
git log
![alt text](<Screenshot (10).png>)
11. git log --oneline
syntax:git log --oneline
purpose:
Compact log view. it shows commit history in short format
Example:
git log --oneline
![alt text](<Screenshot (11).png>)
12. git log --graph
syntax:
git log --graph
purpose:
Graphical branch view.shows the branch structure visually using lines and stars
better version:
git log --graph --oneline --all
![alt text](<Screenshot (12).png>)
13. git show
syntax:git show
purpose:

Shows detail information  of a  specified commit.
example:
git show <commit-id>
![alt text](<Screenshot (13).png>)

14. git diff
syntax: git diff
purpose:
Shows unstaged changes. shows difference between files
example:
git diff
![alt text](<Screenshot (14).png>)
15. git diff --staged
syntax: git  diff --staged
purpose:
Shows staged changes. shows changes that are added but not commited
Example:
git diff --staged
![alt text](<Screenshot (15).png>)

16.git blame
syntax:git blame
purpose:
git blame shows who last modified each line of a file

Example:
git blame filename.txt
![alt text](<Screenshot (16).png>)
17. git reflog
syntax:git reflog
purpose:
Shows reference log history.
 shows the history of where your HEAD and branches have pointed
example:
git reflog
![alt text](<Screenshot (17).png>)

18. git shortlog
syntax:git shortlog
purpose:
Summarizes commit history by author.
example:
git shortlog
![alt text](<Screenshot (18).png>)

file tracking commands
19. git add
syntax:git add
purpose:
Adds specific file or folder  or all files.
example:
git add git file.txt
![alt text](<Screenshot (19).png>)
20. git add .
purpose:
Adds all files.
example:
git add .
![alt text](<Screenshot (20).png>)
21. git add -p
purpose:
Interactive staging.
add changes interactively in small pieces (hunks)
example:
git add -p
![alt text](<Screenshot (21).png>)
22. git restore
syntax: git restore
purpose:
Restores working directory file. used to edit a file but want  to undo changes 
example:
git restore file.txt
![alt text](<Screenshot (23).png>)

23. git restore --staged
syntax: git restore --staged
purpose:
unstages a file (removes from staging area) But keeps your change in the working directroy
used when you accidently did git add.
![alt text](<Screenshot (24).png>)
24. git rm
syntax:git rm
purpose: 
deletes a file from working directory and staging area
used when you want to permenently  removes a file from the repository
![alt text](<Screenshot (25).png>)

25. git mv
syntax: git mv
purpose:
rename a file and move a file to another folder and automatically stage the change
git mv only works for files that are already:
Added using git add
Committed at least once











