# Ejercicio Items

1. Crea una base de datos en Mongo que tenga dos colecciones: `users` y `items`. En la colección de items, cada item debe estar relacionado con un usuario.
2. Crea una API REST en Node.js que se conecte a la base de datos anterior. La API tendrá tres endpoints:

- (POST) /users/login -> debe comprobar en base de datos si las credenciales son correctas, y en caso afirmativo devolver un token
- (POST) /users/register -> debe crear un usuario (si no existe ya) con la contraseña encriptada
- (GET) /items/list -> debe devolver los items del usuario, y sólo debe funcionar si el usuario se ha autentificado
