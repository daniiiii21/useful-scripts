git status 
giving a recap of what was changed lately

git add -A
adds to staging area. -A --> will add all changes to the staging area. If "git status" is run again tells us the changes, that are ready to be commited. 

git commit -m 'Made this and that.'
changes get committed with a message.

git checkout -- .
If everything gets deleted unintended, typing this command into the terminal brings the files right back to the state they were in, when the last commit was made. This even functions when the files and everything is deleted and even if the trash is emptied.

git push origin master
commit is pushed on the server.

git pull origin master
pulling in latestet changes from the server.

git clone https://github.com/<username>/<your-repo>.git
cloning the repository from github to the computer.

git remote -v
Git shows the server address, it thinks where you want it to push to.

git remote set-url origin "link that was copied".
Updating the server addres to where we want to push it to. Link gets copied from Github profile.