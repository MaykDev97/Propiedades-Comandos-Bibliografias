# Pasos y comandos para Hostear una web en github usando lineas de comandos.

Nota: Primero q todo debemos tener sincronizado la cuenta dde git con github... 

## 

Nota: ( Estructura del enlace para q git-pages sepa hostear la pag web)

Nota: (Se toma el nombre del repositorio hasta la ubicacion del index)

-[Landing Page de tipo Portafolio-CV](https://maykdev97.github.io/Portafolio-CV)

## 1) Crear un readme donde va estar la descripcion del sitio y demas, adicionalmente la direccion de como se veria en github. ejemplo Arriba 

touch README.MD

## 2) Iniciar un repo

git init

## 3) Añadir todo los cambios realizados

git add .

## 4) Realizar el primer commit con un mensaje de inicio

git commit -m "Mi Primer Commit"

## 5) Crear rama gh-pages

git branch gh-pages

## 6) Cambiarnos de rama ( main a gh-pages )

git checkout gh-pages

## 7) Agregar el origen remoto

git remote add origin ( Aqui va la direccion q ofrece git al crear un repo nuevo para sincronizar)

## 8) Vincular las ramas q se van a subir (-u "se usa para tener q escribir una sola ves el comando completo con todas las ramas sincronizar")

git push -u origin gh-pages

## 9) Ya por ultimo con abrir el link del README.md donde se especifica la ruta de la web, se abrira la pag ya hosteada