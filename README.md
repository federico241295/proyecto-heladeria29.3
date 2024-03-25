# CLASE 11

## GIT 

## CONFIGURACION GIT (solo se hace 1 vez)


## Nombre de usuario y el correo

    git
    git config --global user.name "Federico Godoy"
    git config --global user.email "federicoegodoy@gmail.com"

## Verificar que todo haya salido bien

git config --get-regexp user

## Quitar config hecha

git configh --global --unset user.email
git configh --global --unset user.name

## Crear repositorio    

git init