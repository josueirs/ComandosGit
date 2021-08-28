# Comandos utiles de Git

1- git init                         <!--Inicializa el repositorio>
2- git add .                        <!--Toma todos los archivos desde el último commit o desde el git init y los prepara para el commit>
3- git reset .                      <!--Revierte lo que hace git add>
4- git commit -m ""                 <!--Toma de fotografía>
5- git checkout -- .                <!--Todos los archivos que se encuentran en el repositorio serán reconstruidos a como estaba el último commit>
6- git log                          <!--listado de commits>
7- git commit --amend               <!--Edita un commit> para salir-> ESC>:>w>q>!
8- git checkout -b rama-nueva       <!--crea una nueva rama 'rama-nueva' y hace cambia a esa rama>
9- git checkout master              <!--repositorio central>
10- git merge "rama"                <!--Combina la rama a la master>
11- git branch -d rama-nueva        <!--borra la rama seleccionada>
12- git push                        <!--Despliega los últimos cambios>
13- git commit -am                  <!--Agrega y pone comentario en un mismo comando>