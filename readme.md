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
git commit -m "Mensaje explicativo"
### Si modificamos un fichero va a parar a la fase Modified
git restore nombre_fichero <- revierte los cambios (como un CTRL + Z)>
git add . <- para volver a la fase Add>
git commit -m "Otro mensaje" <- para volver a la fase commit>

