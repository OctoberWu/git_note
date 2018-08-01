# INSTRUCTIONS:
-------------------------------------------------------
0. Set the account  
`$git config --global user.name "OctoberWu"`  
`$git config --global user.email "october.wu@gmail.com"`  
1. Move to the directory.  
`$git init`  
2. Add the intended files to be traced(supervised)  
`$git add .`  
3. Commit the updated version  
`$git commit -m "Commitment messages"`  
4. Commit to the 'Remote'  
Local Repo --- Remote Repo  
`$git status               "Check the status first`  
`$git push -u origin master "Push local repo to remote repo`  
## Equivalent way  
`$git push origin master`  
`$git checkout master`  
`$git branch -u origin/master`  
## Note:  
'-u' stands for '--set-updatream', and it should be done once.  
Afterward, there's no need to do it again.  


## Note:  
### Get Version  
`$git --verion`  
### Get Status  
`$git status`  
### Make command concise  
### '-a': add   '-m': message  
`$git commit -a -m "the updated messages"`  
### To perceive the differences  
`$git diff`  
### Remove the files(hello.py) from being traced  
`$git rm --cached hello.py`  

