# Git Stash
Git Stash guarda lo que esta eb el repo (WD)en unn area temporal de Git

```bash
git stash
```

## Lista 

```bash
git stash list
```

# .gitignore
Este archivo es una blacklist de archivos.
todos los archivos que coloque dentro del archivo gitignore van a ser descartados

# Git log
Cuando estoy dentro del comando para salir que tocar tecla **q** del teclado

### Para listar un solo commit
git log --oneline -1

### De una fecha en particular
```bash
git log --since="aaa-mm-dd"
git log --after="aaa-mm-dd"
git log --before="aaa-mm-dd"
git log --after="aaa-mm-dd" --before="aaa-mm-dd"
```

```bash
git log --oneline --decorate --all --graph
```

# Corregir la ultima descripcion de commit
si me equivoco en la ultima descripcion del commit puedo corregirlo con git amend

```bash
git commit --amend -m"nuevo comentario corregido"
```

# Add y commit (los dos juntos)
*tengo que tener en el staging area*

```bash
git commit -am "comentario commit"
```

# Git Remote
Ver si tengo el repo remote

```bash
git remote -v
```
## Agregar un remoto a mi repo local
```bash
git remote { alias del remoto } https://github.com/{ususrioGit}/{nombreRepo}
```
## Cambiar nombre del repo remoto
```bash
git remote rename { origin } { it } https://github.com/{ususrioGit}/{nombreRepo}
```
## Borrar repositorio remoto del local
```bash
git remote rm { origin }{ it } https://github.com/{ususrioGit}/{nombreRepo}
```

# BRANCH

```bash
git branch {nombreRama}
```

### Ejemplo
```bash
git branch dev
```

## Cambio de rama
```bash
git switch dev
```
```bash
git chekout <rama>
```

## Creo una rama y me cambio a ella
```bash
git checkout -b nuevaRama
```

## Borrar una rama
```bash



