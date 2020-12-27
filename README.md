<h1>Create a new repository on the command line</h1><br>
echo "# TestGit" >> README.md<br>
git init<br>
git add README.md<br>
git commit -m "first commit"<br>
git branch -M main<br>
git remote add origin https://github.com/Teeratach/TestGit.git<br>
git push -u origin main<br>
<br>
<br>
<h1>Pull sub-branches</h1><br>
git remote add origin https://github.com/Teeratach/TestGit.git <br>
//Assume we have new branches name as B2 <br>
//git "remote name" "branch name"<br>
git pull origin B2<br>
git push -u origin B2<br>
<br>
<br>
<h1>Pull main branches in sub-branches When main changed</h1><br>
git remote add origin https://github.com/Teeratach/TestGit.git <br>
git pull origin main<br>
<br>
<br>
<h1>Request Merge Sub-branche to main</h1><br>
git remote add origin https://github.com/Teeratach/TestGit.git <br>
git merge origin/main<br>
