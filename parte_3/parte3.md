1. Analiza

git status
git add README.md
git commit -m "Actualiza documentación"
git push
Explica qué ocurre en cada instrucción.

git status: en este comando aparecen los cambios que se han realizado dentro del proyecto y que se 
pueden subir a un repositorio.

git add README.md: en este comando agrega el archivo README.md a un commit para poder subirlo a la nube 
en GitHub

git commit -m "Actualiza documentación": se crea el commit con el nombre indicado listo para subirlo a 
la nube.

git push: con este omando todo los archivos que se hayan subido en el commit e incluyendo al commit se 
suben al repositorio en la nube en GitHub.

2. Identifica qué falta
# Caso A
Modificar archivo
↓
git add .
↓
¿?
↓
git push
Indica qué operación falta y explica su función.

Modificar archivo
↓
git add .
↓
git commit -m "nombre del archivo"
↓
git push

sin ningun commit no se puede subir nada a la nube, ese comando nos sirve para hacer un commit

# Caso B
Repositorio GitHub
↓
¿?
↓
Repositorio local
Indica qué operación utilizarías y explica por qué.

Repositorio GitHub
↓
git clone
↓
Repositorio local

este nos permite descargar un repositorio de GitHub a mi computadora creando una copia local con todos sus documentos

# Caso C
Repositorio remoto actualizado
↓
¿?
↓
Repositorio local actualizado
Indica qué operación utilizarías y explica por qué.

Repositorio remoto actualizado
↓
git pull
↓
Repositorio local actualizado

nos permite actualizar el repositorio local con los cambios del repositorio remoto llegando a  
ntegrarlos nuevos commit.
