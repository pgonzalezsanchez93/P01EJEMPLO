# GIT Básico

## Instalación

Instalación desde el asistente de Git

## Comandos para credenciales en nuestro equipo

``` 
git config --global user.name "nombre de usuario"
git config --global user.email "correo usuario"
``` 

## Crear un repositorio Git

``` 
git init
``` 

## Comprobar el estado de Git

Ver la situación en la que estan los cambios desde
el último commit

``` 
git status
``` 

## Añadir archivos al stagging area

Añade todos los cambios pendientes

``` 
git add -A
``` 

## Crear un commit

Para guardar un conjunto de cambios
y crear un punto de control usamos los commit

``` 
git commit -m "mensaje de commit"
```

## Deshacer cambios a partir de los commit

2 opciones

``` 
git reset --soft <código-commit>
```

Con --soft podemos volver a un commit anterior sin
deshacer cambios

Con --hard 


``` 
git reset --hard <código commit>
``` 

