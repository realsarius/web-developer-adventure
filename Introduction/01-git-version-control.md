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
