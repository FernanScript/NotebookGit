# Resumen de los comandos aprendidos en la primera clase de GIT

## Comandos aprendidos
- [git init](#git-init)
- [git status](#git-status)
- [git diff](#git-diff)
- [git add](#git-add)
- [git commit -m ""](#git-commit--m-"")
- [git revert](#git-revert)
- [git reset](#git-reset)
- [¿Que es Staging area?](#¿Qué-es-Staging-area?)
- [¿Que es hash?](#¿Qué-es-hash?)
- [git log](#git-log)
- [git branch -m nombre_rama](#git-branch--m-nombre_rama)
- [git checkout id_commit](#git-checkout-id_commit)
- [git checkout nombre_rama](#git-checkout-nombre_rama)
- [git remote add origin URL](#git-remote-add-origin-URL)
- [git merge](#git-merge)
- [Merge de forma automatica en conflictos](#Merge-de-forma-automatica-en-conflictos)
- [Merge de forma manual en conflictos](#Merge-de-forma-manual-en-conflictos)
- [Pull request](#Pull-request)

## git init
Se utiliza para inicializar la carpeta donde haremos las modificaciones

## git status
Lo utilizo para verficar los archivos que tengo en mi carpeta local.

## git diff
Muestra la diferencias entre la versión anterior guardada con la actual.

## git add
Agrega los archivos o el archivo que quiero tener en mi repositorio.

## git commit -m ""
Describo de manera precisa y concisa los cambios que he hecho.

## git revert
Revierte los cambios que hemos hecho y crea un nuevo commit.

## git reset
Permite deshacer los cambios sin crear un nuevo commit.

## ¿Qué es Staging area?
Es la carpeta local donde estamos haciendo las modificaciones.

## ¿Qué es hash?
Es el número de identificación del commit.

## git log
Me permite ver todos los commits con su hash, autor y fecha de creación.

## git branch -m nombre_rama
Me permite crear una rama.

## git checkout id_commit
Permite volver al commit anterior.

## git checkout nombre_rama
Me permite cambiar de rama.

## git remote add origin URL
Permite agregar tu carpeta con archivos al repositorio del URL.

## git merge
Une dos ramas para mezclar los dos archivos que tengas en distintas ramas.

## Merge de forma automatica en conflictos
Git se da cuenta que existe un conflicto y realiza el merge automáticamente. Sucede cuando se hicieron cambios del mismo archivo en diferentes horas.

## Merge de forma manual en conflictos
Git se da cuenta que existe un conflicto y te envía un mensaje para que tú lo resuelvas. Sucede cuando se hacen cambios en la misma linea del archivo.

## Pull request
Es parecido a un commit por la función que hace. guarda los cambios en la rama del cual hiciste push y la fusiona con otras ramas.
