# Week 6 - Challenge 4

## API REST Things I already know

Crea una API REST que se conecte a una base de datos en MongoDB, para manipular recursos de tipo _cosas que ya sé_. La base de datos tendrá una sola colección, donde almacenará documentos que representarán cosas que hemos aprendido en el bootcamp. Duplica la base de datos para que una sea la de pruebas y otra la de producción.

La API REST debe tener los siguientes endpoints:

[GET] /things -> devuelve el array de cosas que ya sé

[GET] /things/:idThing -> devuelve una cosa que ya sé

[DELETE] /things/:idThing -> borra una cosa que ya sé

[POST] /things -> crea una cosa que ya sé (la recibe en el body)

[PUT] /things -> modifica una cosa que ya sé (la recibe en el body)

Para iniciar la API, el programa debe mostrarle al usuario las siguientes preguntas (utiliza el paquete `inquirer`):

- ¿En qué puerto quieres que se inicie la API? (respuesta por defecto: 4000)
- ¿Qué base de datos quieres usar? (pregunta con varias opciones, una única respuesta)
  - Pruebas
  - Producción
- ¿Quieres permitir que los clientes puedan crear, borrar y modificar? (respuesta de sí o no)
