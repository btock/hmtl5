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
```
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
10. git commit -m "message" = save the changes with a message in order to keep track file modifications
11. git log =  list all performed commit
12. git checkout "SHA commit code"= command to check old commit versions (we have to copy the SHA code from git log in order to return to an old commit)
    a. git checkout master = returns to the last commit
13. git reset "SHA code" = deletes commits (you have to use the SHA code from git log for this)
    a. git reset --soft = simply dont touch our working area
    b. git reset --mixed =  deletes staging area, dont touch working area
    c. git reste --hard = deletes all
```
***
# Branches & fusions

**Branch =** is a version of the code of the project you are working on. These branches help maintain order in version control and manipulate code safely.

Una rama o branch es una versión del código del proyecto sobre el que estás trabajando. Estas ramas ayudan a mantener el orden en el control de versiones y manipular el código de forma segura

**Fusion Branch =** It is the creation of a commit by joining one branch with another.

La fusión en Git combina secuencias de confirmaciones en un solo historial unificado de confirmaciones

***
```
1. git branch = show name branch where you are
2. git branch "branch name" = create a new branch
3. git checkout -b "branch name" = create a new branch a moves to that branch
3. git checkout "branch name" = moves between branches (all commits will be moved to the branch)
4. git branch -D "branch name" = deletes a branch
5. git merge "branch name" = fusion branch with the master ( we have to be positiones in master with git checkout master)
    a. fast forward = simple and automatic, only performs the fusion with no questions
    b. manual merge = long and manual, Before doing the merger you have to go through us
6. 
```
# git & github
***
```
1. git clone (copiamos el link https)= nos sirve para clonar (descargar un proyecto), toma proyecto de github y lo traslada a nuestra computadora
    a. para clonar un proyecto copianos el HTTPS link que viene en el proyecto de github
```
### upload our proyect to github
```
1. crear un repositorio en github
    a. repositorio remoto = se encuentra en github
    b. repositorio local = se encuentra en nuestra computadora
```
![1 create repository](https://github.com/btock/htmlcsstest/assets/14008255/acef8586-848a-4f5f-bc17-5b82aab832dc)
![2 https link github](https://github.com/btock/htmlcsstest/assets/14008255/c5c142b8-f83a-46f0-bc6e-bbf327b1a6d9)
```
2. git remote add origin (paste https link)= vincula nuestro proyecto local con nuestro proyecto remoto
3. git remote -v = muestra la conexion hacia el proyecto de github
4. git remote remove origin = remueve la conexion de proyecto github
```
![3 git remote github](https://github.com/btock/htmlcsstest/assets/14008255/89468f6e-46dd-42aa-828a-fd44e2cbd483)
```
5. git push origin master = envia los commits a gihub (envia de repositorio local a repositorio remoto)
    a. master es el nombre de la rama que queremos subir, si la rama tiene otro nombre entonces lo cambiamos
6. nos solicitara usuario y contrasena de github para subir los cambios
```





