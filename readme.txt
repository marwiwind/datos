Marwiwind@DESKTOP-83I2GN7 MINGW64 ~

$ git status # para ver el status de tu repositorio

$ cd datos # para moverte entre carpetas

$ cd Documents

$ cd datos

$ git status
On branch master
nothing to commit, working tree clean #significa que todo ok

$ git remote -v # para ver lo que está en remoto
origin  https://github.com/marwiwind/datos.git (fetch)
origin  https://github.com/marwiwind/datos.git (push)

$ git add readme.txt # estoy añadiendo mi archivo en local

$ git add . # para añadir todo lo que haya en la carpeta

# git identifica los cambios contando el nº de caracteres y otra cosa y así identifica si algo ha cambiado o no

# git commit -m "el nombre que le quiera poner a mi archivo" #esto en local

### CUANDO MODIFICO Y QUIERO SUBIRLO A GITHUB ###

git add . #subo la carpeta directamente

git commit -m "le pongo nombre" 

git status # lo compruebo

git push origin master # hago la subida a remoto

### CLONACIÓN DE ARCHIVOS ###

creo repositorio que se llama repo_datos

alguien que quiere trabajar con esto se crea un clon online y tiene una copia de ese repositorio

hace un repositorio local y un git add, git commit y git push y lo sube a su repositorio online con sus cambios

si quiere incorporar sus cambios en el repositorio original es hacer un pull request

### CONFLICTOS ###

sole y marta van a trabajar ese repositorio inicial y sacan una copia

ambas hacen sus cambios y hacen sus git add, git commit y git push

si ambas hicieran un pull request al mismo tiempo, el creador tendrá que ver cuál acepta primero
