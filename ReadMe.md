```powershell
git --version
```
powershell> git version 2.49.0.windows.1

## code to add the user account
```powershell
git config --list

git config --global user.name "cr4nb3rrym4st3r"
git config --global user.email "email@address.com"
git config --global core.pager cat
git config --global core.editor "nano"
git config --global pull.rebase false
git config --global fetch.prune true 
```

## code to bring down a repository
```powershell
git clone https://github.com/usernameGeneration/aws-x6-demo.git
```
## code to add new files ready to be committed
```powershell
cd aws-x6-demo
git add .
git status
```
powershell> 
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)     
        new file:   test.txt

## code to actually send the files to github
```powershell
git commit -m 'description of commit'
git push
```

## code to refresh with any external updates
`git pull`
