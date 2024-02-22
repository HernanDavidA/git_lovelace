# Comando para listar las ramas de mi repositorio

- git branch
- git branch -v

# Comando para crear una rama

git branch nombre_rama

# Comando para cambiar de ramas

git checkout nombre_rama
git switch nombre_rama
git checkout -b nombre_rama(Crea la rama y hace el cambio hacia ésta)


# Comando para eliminar una rama

git branch -D nombre_rama

# Comando para cambiar el nombre de una rama 

git branch -M nuevo_nombre

## Comando para eliminar un archivo del main

 git rm --cached index.html

## Comando para crear comandos personalizados 

git config --global alias.lg 'log --oneline'

## Comando para llevar una rama a otra 
git merge nombre_rama
