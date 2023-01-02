# DemoRepo
Demonstration Repository => Demo Repo
This readme is for practice.

## Subheader

Practice commit.

## Notes 

1. git clone *SSH* 
This brings code down from an existing repo.

2. git init
This initializes a repository from your device.

3. git remote add origin *SSH*
This tells the machine what git repo to store in the cloud

4. git status
Tells us what changes haven't been committed and haven't been staged

5. git add .
Adds new files to the list of files to be committed. Can either do one file or . for all files.

6. git commit -m "header" -m "body"
commits changes

7. git push origin main
pushes changes into the main/master branch
This may find errors if one does not have the proper authentication.
May have to use git config user.email "a@b.com"
Also, may need to be sure public ssh key is allowed in my github settings.
Also, need to be sure my private ssh key is connected using the following:

8. eval "$(ssh-agent -s)"
9. ssh-add ~/.ssh/privatekeyname
These add an existing private key to my ssh agent. 

If I need a new key, use: 
10. ssh-keygen -t rsa -b 4096 -C "mperr013@odu.edu"
Be sure to save the new key location to C:\Users\smyle\ .ssh\filename

11. git push origin main
This pushes the changes into the repo online

12. git branch 
Shows branches

13. git checkout -b branchname
builds a new branch

14. git checkout branchname
navigates to branchname

15. git branch -d branchname
deletes branchname

16. git reset file.type
unstages a file that was to be commited. 

17. git reset HEAD~1
undoes a commit.

18. git log
shows all history of commits

19. git pull origin main
Grabs the code from the repo you are working from and makes sure it is up to date.



## Steps

1. open index.html in your browser.
2. have fun!