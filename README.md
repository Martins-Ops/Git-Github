
#  VeeSprout Bug Fix

Details on how I fix the bug introduced in the  VeeSprout's code base
>
>- Created a fork of the Project https://github.com/VeeSprout/Git-Github'
>- Cloned the project on my forked repository's page.
   ``` bash 
git clone https://github.com/Martins-Ops/Git-Github.git
```
>- Created a new branch for the issue fix.
   ``` bash 
git checkout -b Adesanya-Oluwafemi-Martins
```
>- Made the necessary changes to fix the issue within my local repository.
>- Added, committed and Pushed the file to the branch 'Adesanya-Oluwafemi-Martins'
   ``` bash 
git add mine.py
git commit -m "commit messaage"
git push origin Adesanya-Oluwafemi-Martins
```
>- Pulled the latest changes from the remote repository
   ``` bash 
git checkout main
git pull origin main
```
>- Merged the 'Adesanya-Oluwafemi-Martins' branch into main
   ``` bash 
git merge Adesanya-Oluwafemi-Martins
git commit --ammend (to edit merge commit)
git push origin main
```

The procedure above fixed the bug in the VeeSprout codebase