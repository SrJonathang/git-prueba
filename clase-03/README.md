# Clase 03 - 15-06-2022

## REPASO RAMAS Y MERGE

### Crear una rama

    git branch <nombre-rama>

### Listar ramas

    git branch

### MERGE (una fusion de rama)

    **IMPORTANTE**: Tengo en la rama que quiero traerme los cambios. Ej: Si quiero traerme a MASTER lo que vengo haciendo el DEVELOPMENT, tengo que estar en MASTER.

    git merge <rama-que-me-quiero-traer>

## TIPOS DE MERGE

    Fast-Forward: Fusion automatica de las ramas.

    RECURSIVA: Union automatica (No hay colisiones de cambios)

    MANUAL: (Conflictos - Colisiones - Vamos a tener que elegir nosotros con que nos quedamos)

## Para comparar dos ramas

    git diff <rama-1> <rama-2>

## Si quiero crear una rama y moverme a esa rama 

    git checkout -b <nombre-rama>