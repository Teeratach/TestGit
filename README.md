***create a new repository on the command line***<br>
echo "# TestGit" >> README.md<br>
git init<br>
git add README.md<br>
git commit -m "first commit"<br>
git branch -M main<br>
git remote add origin https://github.com/Teeratach/TestGit.git<br>
git push -u origin main<br>
<br>
<br>
***pull branches repository from the command line***<br>
git remote add origin https://github.com/Teeratach/TestGit.git<br>
git pull <remote> <branch><br>
Assume we have new branches name as B2 <br>
git pull origin B2<br>
git push -u origin B2<br>
