-----------------------------------------------------------
<h2>Operadores de comparación</h2>
-----------------------------------------------------------
**Comparadores (1/4)**

> ``==`` igual a  (la recomendacion es usar triple igual) <br>
> ``===`` estrictamente igual a <br>
> ``!=`` distinto a <br>
> ``!==`` estrictamente distinto a <br>
> ``>`` mayor a <br>
> ``<`` menor a <br>
> ``<=`` menor o igual a <br>
> ``>=`` mayor o igual a <br>

-----------------------------------------------------------
**Comparadores (2/4)**

> ``1 === 5; // retorna false.`` <br>
> ``1! == 5; // retorna true.`` <br>
> ``2 < 4; // retorna true.`` <br>
> ``4 < 4; // retorna false.`` <br>
> ``9 <= 9; // retorna true.`` <br>
> ``9 >= 9; // retorna true.`` <br>

-----------------------------------------------------------
<h2>Operadores de lógicos</h2>
-----------------------------------------------------------

**Operadores lógicos && y ||**

A veces es conveniente hacer varias comparaciones en una misma sentencia.

Ejemplos:

 ``var precioA = 400;`` <br>
 ``var precioB = 700;`` <br>
 ``var precioC = 400;`` <br>
 `` `` <br>
 ``(precioA === precioC ) && (precioA < precioB); // Retorna true. ;`` <br>
 ``(precioA === precioC) || (precioA === precioB); // Retorna true. ;`` <br>

 JavaScript evalúa los operadores de izquierda a derecha y se detniene cuando conoce la respuesta.

