**Condicionales - if/Else**

Todo el tiempo tomamos decisiones basados en una condicion.

Ejemplo de un condicional:

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/ejemplo-de-un-condicional-if-else.png?raw=true)

-----------------------------------------------------------
**Sentencia if**

Una sentencia if se utiliza para especificar si un bloque de código se debe ejecutar o no dependiendo del valore de cierta condición.

> ``if (condición) {`` <br>
> ``    //bloque de código a ejecutar;`` <br>
> ``    //si la condición se cumple;`` <br>
> ``}`` <br>


> ``if (llueve) {`` <br>
> ``    //buscar el paraguas;`` <br>
> ``}`` <br>


Ejemplo:

> ``var dia = "Lunes";`` <br>
> ``var precio = 2000;`` <br>
> ```` <br>
> ``if (dia === "Martes") {`` <br>
> ``    alert("Hoy es martes y te toca 10% off!!");`` <br>
> ``    precio = precio * 0.90`` <br>
> ``}`` <br>

en este caso, la condición no se cumple y por lo tanto no se muestra el alert. El precio sigue siendo 2000 pero si fuese martes se le haria un descuento del 10% al comprador.

-----------------------------------------------------------
**Sentencia else**

> ``if (condición) {`` <br>
> ``    //bloque de codigo a ejecutar si la condición se cumple ...`` <br>
> ``} else {`` <br>
> ``    //bloque de codigo a ejecutar si la condición NO se cumple ...`` <br>
> ``}`` <br>

Nota: el Else no necesita de una condición.