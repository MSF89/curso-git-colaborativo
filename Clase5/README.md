# GIT PAGES
En cualquier repo, pueden habilitar un hosting par archivos estaticos (.html/.css/.js). (Aplicaciones vue, app React, Svelt, Angular)
Setting > Pages > Elijo el branch (rama)
A partir de ahi se crea el hosting

### Repositorio magico 
Automagicamente genera una gitpage: < usuario >.github.io

# Issues
Problemas que puede tener la aplicacion. Se pueden crear e interactuar con la comunidad.

# Pull Request
Son modificaciones que esperan revision por los dueños. (Primero tengo que hacer un fork del proyecto).

# proyects
Puede crearse un tablero Kanban (Metodologias agiles creando tareas vinculadas a issues)
 
 # wiki
 Crear una wiki, documentacion del proyecto

 # Tags
 Sirven para buscar las versiones o releases que corresponden a un tag. SOn referencias a un commit especifico en el tiempo.

### Creo un tag en el HEAD
 ```bash
 git tag -a v1.0.0 -m"Aca tengo la version final"
 ```
 ### Creo un tag en un hash(commit) determinado
 ```bash
 git tag -a v0.1.0 6a6a354 -m "Aca agregue una nueva version"
 ```

 ### Listo los commit
 ```bash
 git log <tag> v0.1.0 --oneline
 ```

 ### Listar tags
 ```bash
 git tag
 ```

 ### Ver informacion detallada del tag

 ```bash
 git show <tag>
 ```

 ### Versionado semantico
 https://semver.org/lang/es/

 ### Sube todos los tags, NO recomendado!!
 ```bash
 git push --tags
 ```

 ### Sube un tag en especifico
 ```bash
 git push origin <tag>
 ```
ej: git push origin v1.0.0

# Git Stash
Guardar en un espacio temporal los cambios del working directory
Cuando realizo un Stash, el proyecto vuelve al ultimo commit.

### Creo el Stash
```bash
git stash
```
### Recupero el Stash
```bash
git stash pop
```

### listar Stash guardados
```bash
git stash list
```
### Borrar Stash guardado (no se va a usar)
```bash
git stash drop <id del stash>
```

### Creo una rama a partir del contenido del Stash
El Stash tiene el contenido del working directory
```bash
git stash branch <nombreRama>
```
### Aplicar ultimo Stash o el que yo defina
Nota: Sin borrar el Stash
```bash
git stash apply // Aplica ultimo Stash
```
```bash
git stash apply stash@{2} // Aplica el stash seleccionado
```

# Actualizar Fork
Hacen un Fork y al pasar el tiempo se encuentra desactualizado

### Agrego el remoto a mi repo local
```bash
git remote add upsream <remoto del proyecto original>
```
```bash
git pull upstream <rama>
```
## Clonar un proyecto
```bash 
git clone <direccion-del-repositorio> .
git clone <direccion-del-repositorio> <carpeta>
```
ej:
```bash
git clone git@github.com:mlapeducacionit/Clase05.git .
```


