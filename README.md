#Data Science Toolkit. Ejercicios Git - Github - MArkdown. CIFF
##Crear repositorio campusciff. Nota: El repo campusciff fue creado durante la sesión de clases. A modo de ilustración se muestran los pasos para crear el repo campusciff2.

![Crear Repo1](img/create_repo1.png)

![Crear Repo2](img/create_repo2.png)

##Clonar vuestro repositio en local
- git clone git@github.com:ulisesojeda/campusciff.git

##Añadir al README.md los comanddos utilizados hasta ahora y hacer un coomit inicial con el mensaje commit inicial.
- git add .
- git commit -m "commit initial"

##Subir los cambios al repositorio remoto
- git push origin master

##Crear en el repositorio local un fichero llamado privado.txt
- touch privado.txt

##Crear en el repositorio local una carpeta llamada privada.
- mkdir privada

##Realizar los cambios oportunos para que tanto el archivo como la carpeta sean ignorados por git.
- Para que los ficheros sean ignorados por git deben ser incluidos en fichero .gitignore

##Añadir fichero1.txt al repositorio local
- touch fichero1.txt

## Crear un tag v0.1
- git tag -a v0.1 -m "On tag v0.1"

## Subir los cambios al repositorio remoto
- git push --tag origin master

## Crear una rama v0.2
- git branch v0.2

## Posiciona tu carpeta de trabajo en esta rama
- git checkout v0.2

## Añadir un fichero2.txt en la rama v0.2
- touch fichero2.txt

## Subir los cambios al repositorio remoto
- git add .
- git commit -m "Added fichero1.txt and fichero2.txt"
- git push origin v0.2

## Posicionarse en la rama master
- git checkout master

## Hacer un merge de la rama v0.2 en la rama master
- git merge v0.2

## En la rama master poner Hola en el fichero 1.txt y hacer commit.
- Utilizar vim para modificar fichero1.txt
- git add .
- git commit -m "Modified fichero1.txt"

## Posicionarse en la rama v0.2 y poner Adios en el fichero 1.txt y hacer commit
- git checkout v0.2
- Modificar fichero1.txt con vim
- git add .
- git commit -m "Modified fichero1.txt on branch v0.2"







