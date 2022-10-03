# GIT ADD
### Agregar todo el working directory al staging area o index

```bash
git add .
```
### si borre el archivo fisco del working directori, para quitarlo tengo que hacer lo siguiente
```bash
git rm <nombreArchivo>
```

### si quiero agregar archivos por separado
```bash
git add <nombreArchivo>
```

# ALIAS

```bash
$ git config alias.lg "log --oneline --decorate --all --graph"
```

```bash
$  git config alias.s "status"
```
## Listar Alias disponibles
```bash
$ git config --get-regexp alias
```

## Ayuda de git en local
```bash
$ git help <log>/<status>/<loquesea>
```

## Para quitar un alias o cualquier configuracion
```bash
$ git config --unset alias.<alias>
```
## Modifico manualmente la configuracion de git
```bash
git config --global -e // abre el editor configurado por defecto de git