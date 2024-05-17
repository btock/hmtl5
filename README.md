# pagina en html5 pruebas
es una pagina web de practicas y estilos de html5 y css

***
# git and github tips
***
* git init = start git review
* git checkout -b master or branch name 
    -b (change position to master or branch) 
    master or branch name(move to master or main branch)
* git log = check all commits
* git commit -am "message" = save the commit and leave a message
* git push origin master or branch name = upload proyect to github
* git pull origin master or branch name = download proyect to local computer
* git add/rm <filename>... to update or remove a file created)
***
# HOW TO REVIEW SAVE NEW CHANGES
***
* git status = to check if there is any modified file
* git add -A = to accept all changes
* git commit -am "message" = to leave an updated or message status of the change
* git log = to check if the commit was stored
* git status = to check if there is any other modified file
* git push origin master = to upload the changes to github
***
# DELETE A BRANCH REMOTE FROM GIT
* git branch -a = list all branches from the repository github
* git push origin -d branch-name = deletes a branch from the github project 
***
# starting GIT
***
1. git config --global user.name "name" = assign git name
2. git config --global user.name = verify the git name
3. git config --global user.email "email" = configure email"
4. git config --global user.email = review what email is configured
5. git config --global color.ul true = highlight git results
6. git config --global --list = list all the performed configurations
7. git init= start git to monitor project
8. git status = show the current status of project 
9. git add = add projects files to git in order to create a commit (when a file is modified should use git add and then git commit)
    a. git add "filename" = to add only one file
    b. git add -A = add all of files
10. git commit -m "message" = store the changes with a message in order to keep track file modifications
11. git log =  list all performed commit
12. git checkout "SHA commit code"= command to check old commit versions (we have to copy the SHA code from git log in order to return to an old commit)
    a. git checkout master = returns to the last commit
13. git reset "SHA code" = deletes commits (you have to use the SHA code from git log for this)
    a. git reset --soft = simply dont touch our working area
    b. git reset --mixed =  deletes staging area, dont touch working area
    c. git reste --hard = deletes all
***
