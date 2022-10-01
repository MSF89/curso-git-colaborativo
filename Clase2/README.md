# Claase 2

# Crear repositorio git
Se ejecuta dentro de la raiz del proyecto que quiero versionar

```bash
git init
```
La primera vez que se abre Git se debe configurar nombre y mail de usuario.
Al hacerlo global, todos los repo se van a crear con mismo nombre y mail.
Al hacerlo local solo el repo actual sera con nombre y mail asignado (generalmente en empresas).
Por defecto es local

```bash
git config --global user.name "Soledad"
```

```bash
git config --global user.email "figueroasoledad89@gmail.com"
```

## Como verificar configuracion
```bash
git config --get-regexp user
```

# que pasa con el repo

git status

# Que paso del working directory al stagin area

git add README.md
## todos los archivos

git add .

## Para hacer un commit

git commit : te abre nano y vos le pones la descripcion al commit. con Ctrl+0 guarda y Ctrl+x sale



**Importante**: Git no versiona carpetas vacias
Para que versione la carpeta tengo que crear un archivo *.gitkeep*

# Programas para versionado:
* GitKraken 
* Github Desktop
* Sourcetree


# Creacion de repo en Github

2 nombres magicos
* El de su cuenta git, nombre de usuario: MSF89/MSF89
* El que permite crear un hosting (Configura el Github pages):MSF89/MSF89.github.io

# PASOS BASICOS INICIALES

* git init
* git add README.md || git add .
* git commit -m "descripcion commit" n
* git branch -M main
* git remote add origin https://github.com/MSF89/curso-git-colaborativo.git
* git push -u origin master

# Luedo de los pasos basicos

1. git status
2. git add .
3. git commit -m "descripcion commit"
4. git push