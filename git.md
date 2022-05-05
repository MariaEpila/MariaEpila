#Comandos para git:
###Configurar herramientas:
Sirven para determinar el nombre y el email de la persona que va a crear el repositorio.
-**Configurar el nombre**   $ git config --global user.name "[nombre]" 
-**Configurar email**  $ git config --global user.email "[email]" 
---
###Crear repositorios:
Este comando sirve para crear un repositorio local.
$ git init [project-name] 
---
###Realizar cambios:
Una vez hemos creado el repositorio, git tiene ciertos comandos para realizar commits y trabajar con ellos.
- **subir archivos al área de preparacion ** $ git add [file] 
-**Realizar el commit**  $ git commit -m "[descriptive message]" 
-**Devolver un archivo al directorio de trabajo**  $ git reset [file] 
-**Mostrar diferencias de los archivos del area de trabajo**  $ git diff 
-**Mostrar diferencias entre el area de trabajo y la ultima version del archivo**  $ git diff --staged 
---
###Trabajar con ramas:
-**Devuelve todas las ramas que haya en el repositorio** $ git branch 
-**Crear una nueva rama** $ git branch [branch-name] 
-**Cambiar a la rama a la que se le indique** $ git checkout [branch-name] 
-**Fusionar dos ramas** $ git merge [branch] 
-**Borrar una rama**  $ git branch -d [branch-name] 
