# Week 3 - Challenge 3

## Series

Aquí tienes una aplicación maquetada con HTML y CSS. Se trata de una aplicación que gestiona un listado de series, separándolas entre series vistas y no vistas.

Esta aplicación se alimentará de un fichero JSON que tienes en el archivo `db.json` y que abriremos con [json-server](https://www.npmjs.com/package/json-server).

Deberás hacer una primera petición de datos al servidor y trabajar con el objeto que recibes.

## Milestones

1. Hacer la llamada al servidor para traer los datos.
2. Tienes que mostrar un listado de series, separándolas entre vistas y no vistas. Cada serie tiene que mostrar toda la información que ves en la maqueta. Si la serie es no vista, sus estrellas tienen que estar a 0.
3. El usuario debería poder clicar para valorar la serie con las estrellas que crea necesario. Al clicar en una estrella, la aplicación debe modificar la valoración y la serie debe pasar de no vista a vista (no hay ninguna manera de pasar una serie de vista a no vista).
4. Si el usuario hace click en el icono de la x, la serie se debe eliminar.
5. Intenta reflejar los cambios que haces en tu aplicación en los datos que tiene el servidor.
