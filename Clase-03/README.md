# clase 03 desarrollo colaborativo

## Borrando una rama
```sh
git branch -d nombre-rama  #borra el contenido de una rama cuando este ya esta en otra rama
git branch -D nombre-rama  #fuerza el borrado por mas que el contenido de la rama no aya sido copiado
```
## clonado de un repo

si quiero que la carpeta .git exista en mi local , necesito clonarlo
```sh
git clone url ./ # ./indica el directorio actual

```

# Arreglar un commit mal hecho
```sh
git commit --amend -m "mensaje"
```
