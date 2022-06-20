# Clase 02

hhtps://github.com/abhisheknaiidu/awesome-github-profeile-readme

## Agregar remoto en repositorio local

    git remote add origin <URL>

## Verificar que este copnfigurado el remoto

    git remote
    git remote -v

## Status de Archivos

    UNTRACKED => Archivos que no se agregaron al index (Staging Area) y por consecuencia no se les hara seguimientos

    STAGED=> Archivos que fueron agregados al area temporal o staging area.

    UNMODIFIED => Archivos que se encuentran en el repositorio y que no fueron modificadios.

    MODIFIED => Archivos que se encuentran en el repositorio pero difieren con los que se encuentran actualmente en el directorio de trabajo (Working directory).


![status_archivos](img/3rFpi.png)

# Git amend
 Agregar algo que me olvide en el ultimo commit
    git add . o <archivo>
    git commit --amend

# Trabajar con RAMAS

## Crear una rama

    git branch <nombre>

## Mirar las ramas que tengo en el repo

    git branch

## Como se qen que rama estoy?

    En las consolas tipo linux/unix, voy a tenerlo al costado del path (dev,master...)

## Otra forma es con git status

    git status 
    git branch

## Listar ramas remotas

    git branch -r

## Eliminar RAMAS

ALT + 96=> backtick

'''sh

    git branch -d #Borrar la rama si en el algun momento fue fusionada (merge)
'''


'''sh

    git branch -D #Borro la rama en el caso de que no me deje porque no fue fusionada o "mergeada".

'''

## Subir rama al remoto

        git push origin <nombre.rama>

    Ejemplo: 

        git push origin dev


