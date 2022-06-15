#Comando de consola


## Crear directorios

    mkdir directorio1 directorio2 directorio 3

##  Creo archivos vacios

    touch archivo1 archivo2

## Limpio consola

    clear

## Listar directorios

    ls

## Cambio de directorio

    cd <directorio>

## Salir de un directorio

    cd ..

##Configurar GIT

    Quedar siempre configurada para TODOS los proyectos

    git config --global user.name "Jonathan Gimenez"
    git config --global user.email"srjonathangimenez@gmail.com"

    Crear un repo de GIT, vas a configurar local para ESE REPO

    git config --local user.name "Jonathan Gimenez"
    git config --local user.email"srjonathangimenez@gmail.com"

## Inicializar un proyecto de git (creo un repositorio de git)

Entonces , es un repositorio de git por proyecto. Una carpeta o directorio.

    git init

## Comando ejemplo

    mkdir css js img; touch index.html css/styles.css js/main.js

## Veo el estado de los archivos

     git status

## GIT: No versiona carpetas vacias

    en el caso de querer versionar la carpeta tengo que colocar un archivo. Y estandar por la comunidad es .gitkeep

## Estados de GIT

### Working Directory

    Es el area de trabajo. El area sucia. Donde interactuo con mis archivos y voy creando el codigo.

### Staging Area

    Es una preserva y le dice a git que los prepare para sacarle una foto.

## Para ver la informacion de configuracion

    git config --global -l # Salgo con "Q" del comando (quit)

    git config --global --get-regexp user 