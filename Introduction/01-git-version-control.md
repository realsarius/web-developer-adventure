# About Version Control

What is “version control”, and why should you care? Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later

Terminal commands:

	ls - lists all of the folders

	ls -la - lists all of the files

	cd .. - returns one dir back

	cd - enters a directory

	. - just install in the current directory



On initial install:

	git --version - checks the version of the installed locally git

	git config --global user.name "Your Name" - sets up the name of the user

	git config --global user.email "yourname@somemail.eu" - sets up the mail of the user

	git config --list - lists all the git configurations



For help on commands:

	git help <verb> (e.g. git help config) OR

	git <verb> --help



For initializing the project:

	git init - initializes the git repo in the current folder

	touch .gitignore - creates a git ignore file

	git status - check working tree - both on the git and on local



Add files:

	git add -A - adds all of the files for commiting

	remember - git status - to check the state of the repo



Remove files:

	git reset - removes files to be commited

	git reset somefile.js - removes somefile.js from the commit preparation



Committing:

	git commit -m "This is the commit message" - -m is used to add message



Check log:

	git log - renders commit ids, authors, dates



Clone a remote repo:

	git clone <url> <where to clone>



View info about the repo:

	git remote -v - lists infor about the repo

	git branch -a - lists all of the branches



View changes:

	git diff - shows the difference made in the files



Pull before push ALWAYS:

	git pull origin master



THEN PUSH:

	git push origin master - <origin> name of remote repo <master> the branch that we push to



First time push of the branch:

	git push -u origin <name of the branch> - -u coordinates the two branches (local and on server)



Create a branch:

	git branch <name of the branch>



Checkout a branch:

	git checkout <name of the branch>



Merge a branch:

	git checkout master

	git pull origin master

	git branch --merged - see which branches are merged

	git merge <name of the branch you want to merge>

	git push origin master



Delete a branch:

	git branch -d <name of the branch> - this deletes it locally!!!

	git branch -a - check the repo branches

	git push origin --delete <name of the branch> - this deletes it from the repo!

# Create repositories / Yeni bir depo oluştur

`$ git init [project-name]` - Create a new repository/Yeni bir depo oluştur

`$ git add [file]`  - add file inside your projects/Dosyayı projene ekle yani versiyon oluştur > . adds all

`$ git commit -m "[descriptive message]"` - Commit them to your local repository/Değişiklikleri lokal bilgisayarda kaydet

`$ git status` - Check the status of your repository/Depo'nun durumuna bak"

`$ git clone` - Clone a repository/Depoyu klonla"


# Branches / Dallar

`$ git branch` - List branches/Dalları listele

`$ git branch [branch-name]` - Create a new branch/Yeni bir dal oluştur

`$ git checkout [branch-name]` - Switch to that branch/O dala geç

`$ git merge [branch-name]` - Merge with that branch/Orjinal projeyi o dalla birleştir

`$ git branch -d [branch-name]` - Delete the branch/O dalı sil


# Synchronize changes / Değişiklikleri senkronize et

`$ git fetch [remote]` - Download all history

`$ git merge [remote]/[branch]` - Merge branch on GitHub/GitHub'ta merge'le

`$ git push [remote] [branch]` - Upload local branch to Github/Lokal dal'ı GitHub'a yükle

`$ git pull` - Updates local branch with the latest one on GitHub/GitHub'tan en yenisini indirir.

# Configure / Ayarlar

`$ git config --global user.name "[name]"` - Sets the name when you commit/Commitlediğimizde bizim ismimizi gösterir.

`$ git config --global user.email "[email address]"` - Same with name but email/Yukarıdakinin aynısı ama e-mail için


# History / Geçmiş

`$ git log` - History/Geçmiş

`$ git log --follow [file]` - History for specific file or foler/O dosyanın ya da klasörün geçmişine bak

`$ git diff [first-branch]...[second-branch]` - Differences between branches/Dallar arasındaki değişiklikler

`$ git show [commit]` - That commit's history/O commit'in geçmişi

 ---

## Useful Links

[Git Cheat Sheet - Git](https://training.github.com/)
[Git Cheat Sheet - Education GitHub](https://education.github.com/git-cheat-sheet-education.pdf)
