# Guia git
Para los compañeros de FCT MEDAC

## Bajar repositorio
- git clone https://github.com/jm-willy/guia_git.git

### Subir a repositorio remoto nuevo
- Se crea un repositorio vacio en Gihub, Gitlab, etc

## Crear repositorio local
1. git init | Esto inicia el rastreo de cambios en el directorio por git
2. git add . | Añade todos los archivos del directorio actual(ver consola)
3. git checkout -b local | Crea y cambia a la rama "local"
4. git commit  | "Comete" los cambios de los archivos añadidos a la rama

## Subir a repositorio existente
1. git commit -a | git commit + git add(añade todos los archivos cambiados al commit)
2. git push https://github.com/jm-willy/guia_git.git | Traslada los cambios de la rama local a la rama github "local"

## Numero de branches(ramas)
Cuando se trabaja en proyectos serios, hay que tener 
mas de un "branch" para poder probar cambios sin cargarse 
la rama principal(master o main branch). Esta rama "main"
ha de ser funcional para clientes, para bajarselo, etc.

Por ejemplo, cuando clonemos un repositorio, creamos
una rama para desarrollar y dejamos una principal:
1. git clone
2. git init
3. git add .
4. git checkout -b main-local
5. git checkout -b dev-local

## Merge(unir) branches
1. git checkout main-local | Para cambiar una rama hace falta estar en ella
2. git merge dev-local main-local | Mete los cambios de "dev-local" en "main-local"
3. git push https://github.com/jm-willy/guia_git.git dev | Traslada los cambios de la rama "main-local" a la rama github "dev" O TAMBIEN:
4. git push https://github.com/jm-willy/guia_git.git main | Traslada los cambios de la rama "main-local" a la rama github "main"




