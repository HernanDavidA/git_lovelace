#Comandos de git

## Comando para ver la version de git

- git -v
- git --version


## Comandos para la configuracion inicial de git

- git config --global user.name "Your name"
- git config --global user.email "Your email"

## Comando para editar o ver la configuracion de git
Para salir del edit ctrl + 0 y ctrl + x y si es VIM esc + :wq
- git config --global --edit
- git config --global --list

## Como iniciar git en un directorio

-git init

## Comando para conocer el estado de nuestros archivos

- git status

## Comando para listar las versiones de mi proyecto

- git log 
- git log --oneline


## Comandos para cambiar de version

-git checkout <Numero o ID del commit de la rama>
## Pasos para crear una nueva version de nuestro codigo

1. Agregar todos los archivos al commit

- git add .
- git add \*.js
- git index.js

2. Tomar la foto del codigo (Crear una nueva version)

- git commit -m "Nombre del commit"



## Merge 

El proceso de una union de dos ramas


## Conflicto

Se ocurre cuando dos rams han realizado cambios incompatibles en el mismo segmento de un archivo y luego intentas fusionar estas ramas con un comando merge


