# PIA - NUEVAS TECNOLOGÍAS

## Descripción

Servicio notificador de Afis para usuarios que se registren a la plataforma mediante su correo electrónico.

## Funcionamiento

La información será retribuida mediante un scrapper escrito en python y despues de ser procesada, será mandada a un servidor hecho en node.js con express.js donde se tendrán endpoints para comunicar el servicio a la base de datos SQL. En el frontend tenemos una vista simple corriendo sobre react que registrará los emails de los interesados y los enviará a otro endpoint dedicado del servidor.

## Estructura

Cada carpeta es un submodulo aparte con el proyecto por separado en cada uno de ellos.


