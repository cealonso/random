# Obtención de un Número aleatorio en JS

Devuelve un número aleatorio dentro de un rango de valores definido por min y max.

    function randomInteger(min, max) {
      return Math.floor(Math.random() * (max - min + 1)) + min;
    }
