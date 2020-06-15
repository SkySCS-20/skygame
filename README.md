# skygame
SkyGame

# Instal Choco

```
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

# Install Git
```
choco install git -y
```
# Install Visual studio code
```
choco install vscode -y
```
# Start VSCode
```
code .
```
# Install extension VSCode
```
code --install-extension docsmsft.docs-markdown
code --install-extension ms-python.python
code --install-extension eamodio.gitlens
```
# Setup Git
```
git config --global user.name "UserGit"
git config --global user.email "email@git.ro"
git init // start tracking current directory
git add -A // add all files in current directory to staging area, making them available for commit
git commit -m "Upload" // commit your changes
git remote add origin https://github.com/skyscs-20/skygame // add remote repository URL which contains the required details
git pull origin master // always pull from remote before pushing
git push -u origin master // publish changes to your remote repository
Fix push : git push --force-with-lease
```
6.15