# Buenas Practicas
https://medium.com/@jmz12/buenas-pr%C3%A1cticas-para-commits-5eb4c86b9a47

# Borrar y cambiar nombre archivos desde el bash con git
```bash
git mv <nombreOriginal> <nombreNuevo>
```
```bash
git rm <archivo>
```

# Checkout otros usos
```bash
git checkout -- .
```
# Recupero archivos de la historia.
git checkout <hash> <nombre-archivo>

# Reset


## Soft
Saca los archivos del hash indicado y todo los subsiguientes y los deja en el working directory

```bash
git reset --soft <hash>
```

## Mixed
Es por defecto. si no coloco --mixed es el que hace por defecto
```bash
git reser --mixed <hash>
```
