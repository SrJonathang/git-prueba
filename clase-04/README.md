# Clase 04

    2 tipos de apuntadores

    Estaticos -> Ramas locales como remotas.
    Dinamicos -> HEAD

## TAGS 
    Nos sirven para marcar algun commit que tengo cierta importancia.
    Tambien me sirve para marcar versiones o releases.

## Crear TAG

    git tag v1.1

## Eliminar TAG

    git tag -d v1.1

### Versionado semantico
Si no le coloco el HAS me lo va a poner en el ultimo commit de la rama actual.

    git tag -a v1.0.0 -m "Version 1.0.0 - Aplicacion funcionando"
    git tag -a v0.1.0 <HASH> -m "Version beta de nuetras aplicacion"

### Para mostrar los tags

    git tag

### Version larga para mostrar los tags

    git tag -n

### Para subir todos los tags
**IMPORTANTE¨**: No recomendad salvo que sea lo que estoy haciendo

    git tag --tags

## Subir un tag en particular

    git push origin <tag_name>

