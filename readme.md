# Instrucciones de GIT

## Instrucciones esenciales
### Configuración de git

git config --global init.defaultBranch main <- rama por defecto>


### Iniciar el repositorio
git init <- iniciar el repositorio
### Añadir ficheros a la fase Added
git add readme.md
git add *.html
git add .
git add --all
### Fichero para ignorar lo que no nos interese
.gitignore

### Subir a la fase "commit" = validación

### Si modificamos un fichero va a parar a la fase Modified
git restore nombre_fichero <- revierte los cambios (como un CTRL + Z)>
git add . <- para volver a la fase Add>
git commit -m "Otro mensaje" <- para volver a la fase commit>
git commit -a -m "nuevo mensaje"


## Instrucciones de control
git status
git log <- historial de commit extendido>
git log --oneline <- historial de commits resumido>
git diff <- muestra las diferencias>

## Intrucciones para subir ficheros a un repositorio en la nube
git remote add origin https://github.com/classesdeferran/instrucciones-git-github-2025.git  

## Instrucciones para las ramas
git branch <- obtener las ramas del proyecto>

git branch -M main <- cambiar el nombre a la rama actual (pasará a ser main)>
git checkout nueva_rama <- cambia a una rama existente>
git switch -c rama-3 <- crea la rama y salta hasta ella>

git branch -D rama_a_borrar <- borra una rama>
