Healthcare Application for connecting Hospitals in India Author - Ritu Mahajan from z+
$ git config --global user.name "rituy-mahajan"
$ git config --global user.email "rituymahajan@gmail.com"
$ git config --list

$ git config --global user.name "rituy-mahajan" $ git config --global user.email "rituymahajan@gmail.com" $ git config --list git clone [httpsCommand] git status untracked-modified-staged-unmodified git add filename git commit -m message
git pull origin main
git push origin main --force

//ls -a: Get-ChildItem -Force Get-ChildItem -Directory Get-ChildItem -File

//day 2:
git commit -m "Add Initaial Files"
git remote add origin https://github.com/rituy-mahajan/LocalRepository.git
git remote -v
git branch
git branch -M "newName" //rename branch Name git push origin main
git push -u origin main
git push;


// Branch


git branch
git branch -M "existing Branch /main"
git checkout "feature1"
//to navigate through existing branches git checkout -b "feature1" // to create new branch and navigate
git diff "beach to compare"
git push origin "branch to upload remotely"
git pull origin "branch to download locally"

//merge
git merge "branch name"

//check all commit list git log

//Undoing merges
git reset
git reset filename
git reset HEAD~2 git reset git reset -hard (commit hash)
