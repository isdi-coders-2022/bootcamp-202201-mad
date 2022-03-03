# Challenge 4 Week 7

## Series API part 2

Añade los siguientes endpoints a la API de series:

### Plataformas

[PUT] /platforms/:idPlatform : para actualizar una plataforma (sólo administrador)

### Series

- [GET] /series/viewed: lista todas las series del usuario ya vistas
- [GET] /series/pending: lista todas las series del usuario no vistas
- [PUT] /series/:idSerie : para actualizar una serie (sólo administrador)
- [PATCH] /series/view/:idSerie : para marcar una serie como vista por el usuario

Valida todas las requests necesarias con Joi
