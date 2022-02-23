# Week 6 - Challenge 2

## Calculadora WebService

Crea una calculadora en Node en forma de webservice. El programa debe recibir dos números por query params (p.e. http://localhost:8000/calculator?a=6&b=3), y devolver el siguiente HTML:

Resultados:

6 + 3 = 9

6 - 3 = 3

6 \* 3 = 18

6 / 3 = 2

Si el usuario no ha proporcionado alguno de los números o éstos no son de tipo número, la aplicación debe devolver un HTML con un mensaje de error e interrumpir la ejecución del programa con un código de error.

La app debe abrirse en un puerto por defecto que esté configurado como variable de entorno, pero también se tiene que poder decir expresamente por línea de comandos en qué puerto queremos que se abra (p.e., `node . --port 4000`). Usar el paquete `commander`.

Si la request no va a /calculator, la app debe responder con un 404.
