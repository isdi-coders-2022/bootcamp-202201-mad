# Ejercicio calculadora Express

Refactoriza el ejercicio del WebService Calculadora usando Express.

Habrá un endpoint para cada operación (`/sum`, `/substraction`, `/multiply` y `/division`), y responderán a peticiones GET. Los dos números se seguirán enviando por query params.

Si se hace cualquier petición a esos endpoints con un método que no sea GET, debemos devolver un status 403 y un objeto JSON con esta forma:

```
{
    error: true,
    message: (el que quieras)
}
```

Si se hace una petición a un endpoint que no exista, se debe devolver un error similar al anterior, con un status 404.

Si no se pasan los números por query params, se debe devolver un error similar al anterior, con un status 400.

Usa debug, chalk y morgan. Modulariza siguiendo el principio de responsabilidad única.
