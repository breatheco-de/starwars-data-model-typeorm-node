# Blog Base de datos de Starwars 

Dentro del directorio `./entities` encontrarás una clase `./entities/User.js` que describe un ejemplo de base de datos de usuarios (tabla).

Aquí tenéis un video de 4 minutos explicando que es UML [https://www.youtube.com/watch?v=UI6lqHOVHic](https://www.youtube.com/watch?v=UI6lqHOVHic)

Vamos a crear un diagrama de relación de entidades para la base de datos del Blog de StarWars, un diagrama muy similar a este:

![Starwars Diagram](https://github.com/breatheco-de/exercise-starwars-data-modeling/blob/master/assets/example.png?raw=true)
[Click to open diagram](https://app.quickdatabasediagrams.com/#/d/LxNXQZ)

> 🔥Puedes utilizar esta herramienta GRATUITA para practicar tu diagrama por primera vez: https://app.quickdatabasediagrams.com/#/d/

## 💻 Instalación

Este boilerplate ya viene con todo lo necesario: una base de datos postgre, la configuración de typescript y la configuración de TypeORM.

Cada vez que quieras generar tu diagrama sólo tienes que escribir `$ npm run diagram` y se imprimirá un enlace URL a la imagen de tu diagrama.

## Instrucciones

Comenzaremos leyendo la documentación sobre [how to create entities using TypeORM](https://typeorm.io/#/entities).

Tu trabajo es actualizar el directorio `./entities/` con los archivos y el código necesarios para replicar el modelo de datos de starwars.

El proyecto está utilizando la biblioteca [TypeORM Node.js library](https://typeorm.io/#/) para generar la base de datos.

- Tu proyecto debe tener una tabla `User` que representará a los usuarios de tu blog.
- Los usuarios de tu blog podrán iniciar sesión, guardar sus planetas y personajes favoritos.
- La base de datos debe almacenar los favoritos de los usuarios.
- La base de datos debe almacenar los personajes y planetas.
- ¿Qué otras tablas crees que le puede ir bien tener a un blog como este?
- ¿Qué propiedades deberían ir dentro de la tabla de usuarios? o ¿Que propiedades deberian ir dentro de la tabla de personajes o de favoritos?
- ¿Cuáles son las relaciones entre esas dos tablas?
- Por favor, añade al menos 4 modelos con todas sus propiedades.
- Genera el archivo "diagram.png" al final ejecutando `$ npm run diagram` en la consola.

