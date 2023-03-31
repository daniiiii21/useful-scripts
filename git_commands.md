creating a new repository on the command line:

echo "# presentation" >> README.md
* git init (initializes a new empty Git repository.)
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/<username>/<repository>.git
* git push -u origin main

pushing an existing repository from the command line:

* git remote add origin https://github.com/<username>/<repository>.git
* git branch -M main
* git push -u origin main

git status --> giving a recap of what was changed lately

git add -A --> adds to staging area. -A --> will add all changes to the staging area. If "git status" is run again tells us the changes, that are ready to be commited. 

git commit -m 'Made this and that.' --> changes get committed with a message.

git checkout -- . --> If everything gets deleted unintended, typing this command into the terminal brings the files right back to the state they were in, when the last commit was made. This even functions when the files and everything is deleted and even if the trash is emptied.

git push origin master(main) --> commit is pushed on the server.

git pull origin master(main) --> pulling in latestet changes from the server.

git clone https://github.com/<username>/<your-repo>.git --> cloning the repository from github to the computer.

git remote -v --> Git shows the server address, it thinks where you want it to push to.

git remote set-url origin "link that was copied". --> Updating the server addres to where we want to push it to. Link gets copied from Github profile.