Describe que hacen los siguientes comandos de git, escribe su descripcion al frente en una sola linea.

git status: Este comando se usa para obtener el estado actual del repositorio

git clone:Se usa para copiar un repositorio. Si el repositorio está en un servidor remoto, usa:
git clone nombredeusuario@host:/path/to/repository
          https://github.com/ada-school/git-practice

git pull:fusiona todos los cambios que se han hecho en el repositorio remoto con el directorio de trabajo local.
git pull

git checkout:Crea ramas y te ayuda a navegar entre ellas. Por ejemplo, el siguiente comando crea una nueva y automáticamente se cambia a ella:
command git checkout -b <branch-name>

git log:se usa para ver el historial del repositorio listando ciertos detalles de la confirmación. Al ejecutar el comando se obtiene una salida como ésta:
commit 15f4b6c44b3c8344caasdac9e4be13246e21sadw
Author: Alex Hunter <alexh@gmail.com>
Date:   Mon Oct 1 12:56:29 2016 -0600

git branch: se usa para listar, crear o borrar ramas. Por ejemplo, si quieres listar todas las ramas presentes en el repositorio, el comando debería verse así:
git branch

git add:se usa para agregar archivos al área de preparación. 

git commit:creará una instantánea de los cambios y la guardará en el directorio git.
ejemplo:git commit –m “El mensaje que acompaña al commit va aquí”

git push:se usa para enviar confirmaciones locales a la rama maestra del repositorio remoto. Aquí está la estructura básica del código:
git push  origin <master>

git merge:se usa para fusionar una rama con otra rama activa:git merge <branch-name>
