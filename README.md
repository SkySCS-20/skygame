# skygame
SkyGame


# Setup Git

git config --global user.name "UserGit"

git config --global user.email "email@git.ro"

git init // start tracking current directory

git add -A // add all files in current directory to staging area, making them available for commit

git commit -m "Upload" // commit your changes

git remote add origin https://github.com/skyscs-20/skygame // add remote repository URL which contains the required details

git pull origin master // always pull from remote before pushing

git push -u origin master // publish changes to your remote repository

Fix push : git push --force-with-lease