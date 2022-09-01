# demo to create a git repo locally.

created a repo locally. staged. commited and pushed all changes to github as follows
1. cd demo-repo2
2. git init  # to initialize git in this local repo
3. created  README.md 
4. add some lines
5. git add .  # to stage the changes 
6. git commit -m "adding readme file for our new locally created repo"
7. git push origin master , ah !  but origin not set yet.

8. go to github and create a new repo called demo-repo2 and cpopy the url

9. git remote add origin <ssh url> 

10. git remote -v # to check the remote repositories connected to the repo locally. 

11. git push origin master ,  but if you add a parameter -u ( upstream)
it will remember the master to which your tryna push. 
