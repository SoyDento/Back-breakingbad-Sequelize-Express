# BreakingBad

## Express - PostgreSQL - Sequelize

## Descripción

Desarrollamos una API que nos permite realizar las siguientes acciones:

* Consultar personajes existentes
* Crear nuevos personajes
* Actualizar y modificar características de los personajes creados
* Eliminar personajes


## Completa la aplicación

Esta aplicación está ambientada en la serie BreakingBad. Tiene una página principal que nos va a mostrar personajes (hasta 8) de la serie y algo de información sobre a ellas. Al clickear en alguno, iremos a un "Detail" que nos va a mostrar más datos de los personajes.
Tambíen creamos una Database para introducir nuevos personales.

La aplicación va a contar con tres rutas:

 - **GET:"/characters"**: nos trae todos los personales.
 - **GET:"/characters/:id"**: nos trae el detalle nuestro personaje elegido.
 - **GET:"/occupations"**: nos trae todas las ocupaciones.
 - **POST:"/characters"**: creación de un peronaje.
 - **DELETE:"/removeChar"**: eliminación de un peronaje.
 - **PUT:"/:attribute"**: modificación de atributos de un peronaje.

Para comenzar:

`npm install`

`npm test` ( Para correr los tests. Podes pasarle como argumento el nombre del test a correr. Por ejemplo, `npm test App` va a correr solamente los tests del archivo App )

Para levantar la app, por si queres ver cómo va la página (recordá que para aprobar tienen que pasar los tests):

`npm start`


MUCHAS GRACIAS A LOS CREADORES DE LA DB Y LA CONSIGNA DE ESTE ENTRENAMIENTO !!
