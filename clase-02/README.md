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