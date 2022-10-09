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

## Hard
Destructivo: Peligroso, mucho cuidado
```git reset --hard <hash>
```
# Reflog 
Un log de las referencias de todo lo que ha sucedido en orden cronologico
```bash
git reflog
```

# ReBase
* Ordenar commits
* Corregir mensajes de los commits
* Unir commits
* Separar commits
Siempre tengo que estar en la rama en la que quiero integrar los cambios

Para traer los cambios:
```bash
git rebase master
```
Para abortar en un conflicto
```bash
git rebase --abort
```
Para continuar con el rebase para finalizar
```bash
git rebase --continue
```
## Rebase Interactivo
```bash
git rebase -i
```
# Crear un submodulo

```bash
git clone https:
```
