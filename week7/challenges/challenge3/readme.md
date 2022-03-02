# Challenge 3 Week 7

## Series API

Construye una API REST que permita gestionar un listado de series vistas. La API tiene que manejar las siguientes entidades:

- Usuarios
- Plataformas
- Series
  Cada usuario tendrá (además de lo que creas conveniente), un campo indicando si es administrador o no y un campo que almacenará las series que ha visto.
  Cada serie pertenece a una plataforma.
  Endpoints (todos están protegidos por JWT menos los que se indiquen como abiertos):

### Usuarios

[POST] /users/login: endpoint abierto, para iniciar sesión
[POST] /users/register: endpoint abierto, para crear un usuario

### Plataformas

[GET] /platforms: lista todas las plataformas de la base de datos
[POST] /platforms: para crear una nueva plataforma (sólo administrador)
[DELETE] /platforms/:idPlatform : para borrar una plataforma (sólo administrador)

### Series

[GET] /series: lista todas las series del usuario, vistas o no
[POST] /series: para crear una nueva serie (sólo administrador)
[DELETE] /series/:idSerie : para borrar una serie (sólo administrador)

- Haz tests unitarios de todos los middlewares
- Haz tests de integración de todos los endpoints
