#Git Commands 
Healthcare Application for connecting Hospitals in India
Author - Ritu Mahajan from z+
<br>
$ git config --global user.name "rituy-mahajan"
<br>
$ git config --global user.email "rituymahajan@gmail.com"
<br>
$ git config --list
<br>

$ git config --global user.name "rituy-mahajan"
$ git config --global user.email "rituymahajan@gmail.com"
$ git config --list
git clone [httpsCommand]
git status
untracked-modified-staged-unmodified
git add filename
git commit -m message
<br>
git pull origin main
<br>
 git push origin main --force

//ls -a:
 Get-ChildItem -Force
 Get-ChildItem -Directory
 Get-ChildItem -File
<br>

 //day 2:  
 git commit -m "Add Initaial Files"
 <br>
 git remote add origin https://github.com/rituy-mahajan/LocalRepository.git
 <br>
  git remote -v
  <br>
  git branch
  <br>
  git branch -M "newName"   //rename branch Name
  git push origin main <br>
  git push -u origin main <br>
  git push;
  <br>
  <br>
  
// Branch

<br>
git branch <br>
git branch -M "existing Branch /main" <br>
git checkout "feature1" <br>  //to navigate through existing branches
 git checkout -b "feature1"  // to create new branch and navigate
<br>
git diff "beach to compare"
<br>
git push origin "branch to upload remotely"
<br>
git pull origin "branch to download locally"
<br><br>
//merge
<br>
git merge "branch name"
<br><br>
//check all commit list
git log
<br><br>
//Undoing merges

git reset<br>
git reset filename<br>
git reset HEAD~2
git reset <commit hash>
git reset -hard (commit hash)



