<h1>Iterador FOR, FOREACH y FOR OF</h1>

-----------------------------------------------------------
Recorrer un Array usando un *for*, *forEach* o un *for of*

-----------------------------------------------------------
**Recorrer un Array usando for**

> ``for (var i = 0; i < marcas.length; i++) {`` <br>
> ``    console.log(marcas[i]);`` <br>
> ``}`` <br>

Esta es la forma mas tradicional o antigua de recorrer un array.

Si bien la sintáxis del *for* es menos amigable con respecto a otros métodos más modernos utilizados para recorrer arrays (ej: forEach), hay algunos casos en los que puede ser útil debido a su flexibilidad.

Nota: el nombre de la variable *i* es arbitraria; por ejemplo, se le podría haber llamado *indice*.

-----------------------------------------------------------
**Recorrer un Array usando forEach**

> ``marcas.forEach(function(item) { `` <br>
> ``    console.log(item);`` <br>
> ``})`` <br>

El metodo forEach esta disponible desde la version ES5 de JavaScript (2009) y funciona a partir de IE9. Solo se puede usar para recorrer arrays (a diferencia de for que tiene otros usos).

Nota: el nombre del parámetro item es arbitrario; por ejemplo, se le podría haber llamado marca.

-----------------------------------------------------------
**Recorrer un Array usando un for of**

> ``for (var item of marcas) {`` <br>
> ``    console.log(item);`` <br>
> ``}`` <br>

El for of está disponible desde la version ES6 de JavaScript (2015) y no funciona en ninguna versión de IE. Posiblemente es la sintaxis mas sencilla que existe para recorrer arrays.

Nota: El nombre de la variable item es arbitraria; por ejemplo, se le podria haber llamado marca.










