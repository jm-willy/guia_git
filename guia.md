# Guia git
Para los compañeros de FCT MEDAC

### Bajar repositorio
- git clone https://github.com/jm-willy/guia_git.git

### Subir a repositorio nuevo
- Se crea un repositorio vacio en Gihun, Gitlab, etc

### Subir a repositorio existente
1. git init
2. git add .
3. git checkout -b main
4. git commit
5. git push https://github.com/jm-willy/guia_git.git

#### Numero de branches(ramas)
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

### Merge(unir) branches
1. git checkout main-local
2. git merge dev-local
3. git push https://github.com/jm-willy/guia_git.git dev




