# Obtención de un Número aleatorio en JS

Devuelve un número aleatorio definido dentro de un rango de valores min y max.

    function randomInteger(min, max) {
      return Math.floor(Math.random() * (max - min + 1)) + min;
    }
