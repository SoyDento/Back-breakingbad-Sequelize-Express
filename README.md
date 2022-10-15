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


## REACT - REDUX

Vas a trabajar en los siguientes archivos (Cada archivo tiene su archivo de test correspondiente). Para el desarrollo de esta aplicación, te recomendamos seguir este camino:

1. App.js
2. components/Nav/Nav.jsx
3. redux/actions/index.js
4. redux/reducer/index.js
5. components/Houses/Houses.jsx
6. components/HouseCard/HouseCard.jsx
7. components/HouseDetail/HouseDetail.jsx
8. components/CharacterCard/CharacterCard.jsx
9. components/CreateHouse/CreateHouse.jsx

Vas a tener que ir leyendo **cada archivo de test por componente** y la descripción de cada uno para ir avanzando.

>Los tests se encuentran comentados. Para poder correrlos tendras que cambiar el `xdescribe` de cada archivo .test.js por `describe`.

>Lee bien los tests y lo que piden, sobre todo los detalles.


>Esta aplicacion esta pensada para que pasen los tests, y que tenga la funcionalidad que buscamos, NO tiene estilos por lo que los componentes se veran muy precarios. Luego de rendir, los animo a que le den los estilos que gusten!

>Debes completar 44 de los 55 tests que se encuentran en el CP

MUCHAS GRACIAS A LOS CREADORES DE LA DB Y LA CONSIGNA DE ESTE ENTRENAMIENTO !!
