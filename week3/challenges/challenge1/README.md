# Week 3 - Challenge 1

# GoT DOM

Tendrás que programar esta interfaz de usuario para que refleje el modelo de datos que diseñaste en el anterior ejercicio.

0. Crea los siguientes archivos JS y haz que funcionen como módulos mediante import y export:

- Personaje.js, Rey.js, Luchador.js, Asesor.js, Escudero.js (mete dentro cada clase)
- personajes.js (crea dentro un array con todos los personajes del ejercicio anterior)
- index.js (aquí va todo el resto del enunciado, y éste será el punto de entrada)

1. Haz que por cada personaje del array se muestre la ficha correspondiente en el navegador:
   - En el elemento con clase `emoji` tiene que aparecer uno de estos emojis dependiendo del tipo de personaje: 👑 🗡 🎓 🛡
   - Si el personaje está muerto, su foto debe aparecer cabeza abajo (haz el CSS necesario);
   - En la lista con clase `metadata`, haz que sólo aparezcan los `li` correspondientes al personaje.
2. Cuando el usuario haga clic en el botón "muere", tiene que cambiar el estado del personaje, y la interfaz debe reflejar el cambio.
3. Cuando el usuario haga clic en el botón "habla", el elemento con clase `comunicaciones` debe aparecer con el texto y la imagen correspondientes. Haz que este elemento `comunicaciones` tenga la clase `on` durante 2 segundos y luego se le quite.
