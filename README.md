# KODOTI-XCHANGE
Este proyecto ha sido creado para el curso de KODOTI y nos permite generar un componente para visualizar
el tipo de cambio del dolar americano de algunos paises.

Si quieres aprender sobre TypeScript participa de nuestro curso en el siguiente enlace:

[https://kodoti.com/cursos/typescript-desde-cero](https://kodoti.com/cursos/typescript-desde-cero)

## Sobre el proyecto
Este integra WebPack para facilitar el desarrollo de nuestro proyecto permitiendo compilar el proyecto cuando queramos pasarlo a producción y levantar un servidor local para nuestra etapa de desarrollo.

Basicamente para integrar webpack necesitamos los siguientes paquetes adicionales:

* ts-loader
* typescript
* webpack
* webpack-cli
* webpack-dev-server

La ventaja de usar el servidor local de webpack es que permite refrescar los cambios que hagamos automáticamente en un servidor local evitando de esta manera tener que hacer build ante cada cambio.

## Servidor local de desarrollo
Posicionarse desde la consola en la ruta del proyecto y ejecutar el comando `npm run dev`.

## Modo producción
Cuando estemos listo para generar todo nuestro proyecto basta con ejecutar `npm run build` y se generar un compilado en un solo archivo en la siguiente ruta build/bundle.js

KODOTI - ¡Aprende más, haciendo pequeños proyectos!


