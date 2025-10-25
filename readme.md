# Instrucciones de GIT

## Instrucciones esenciales
### Configuración de git
> git config global user.name tu_nombre
> git config global user.name "nombre1 nombre2"
> git config global user.email tu_email@tu_proveedor.com
> git config global core.editor "code --wait"
> git config global core.autocrlf true <- en windows o input <- en mac o linux 
> git config --global init.defaultBranch main <- establecer la rama por defecto>


### Iniciar el repositorio
> git init <- iniciar el repositorio

### Fichero para ignorar lo que no nos interese
> .gitignore

### Mover ficheros a la fase Added
> git add readme.md
> git add *.html
> git add .
> git add --all
> git restore --staged nombre_fichero <- retorna a la fase inicial>

### Mover ficheros a la fase "commit" = validación
> git restore nombre_fichero <- revierte los cambios respecto el anterior commit (como un CTRL + Z)>
> git add . <- para volver a la fase Add>
> git commit -m "Otro mensaje" <- para pasar a la fase commit>
> git commit -a -m "nuevo mensaje" 


## Instrucciones informativas
> git status <- estado del repositorio>
> git log <- historial de commit extendido>
> git log --oneline <- historial de commits resumido>
> git log --oneline --graph <- historial de commits resumido con esquema de ramas>
> git diff <- muestra las diferencias entre versiones de los ficheros>

## Intrucciones para subir ficheros a un repositorio en la nube
> git remote add origin https://github.com/tu_cuenta/tu_repo.git  

## Instrucciones para las ramas
> git branch <- obtener las ramas del proyecto>
> git branch nueva_rama_1 <- crea una rama>
> git checkout nueva_rama_1 <- cambia a una rama existente>
> git switch -c nueva_rama_1 <- crea la rama y salta hasta ella>
> git branch -M main <- cambiar el nombre a la rama actual (pasará a ser main)>
> git branch -D rama_a_borrar <- borra una rama>
> git merge otra_rama <- une la rama otra_rama a la rama actual >
