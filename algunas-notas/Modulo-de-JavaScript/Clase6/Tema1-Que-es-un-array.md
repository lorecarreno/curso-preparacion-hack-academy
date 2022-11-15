**Que es un Array?**


- Es una *estructura de datos* que permite almacenar un *conjunto* de valores en formato lkista. Se los puede pensar como una "lista de elementos".

- En lugar de manipular los valores por separado, se manipula el conjunto.

- El largo de los arrays es variable y pueden contener elementos repetidos.

- Los valores contenidos en un array no tienen por qué ser del mismo tipo.
Pueden ser strings, numbers, booleans, funciones, otros arrays, etc (todo mezclado).
De todas maneras, lo más usual es que los elementos de un array sean del mismo tipo.

- En español se les llama "Arreglos" (o incluso "Vectores").

-----------------------------------------------------------
**Cómo se crea un Array?**

*Metodo 1:*

Se utilizan corchetes [] y se pasan los valores separados por comas ",".

> ``var marcas = ["BMW","Peugeot","Chebrolet","Subaru","Nissan"];`` 

*Metodo 2:*

Se utilizan las palabras *new* y *Array*, y se pasan los valores separados por comas ",".

> ``var marcas = new Array("BMW","Peugeot","Chebrolet","Subaru","Nissan");``

Ambos metodos son equivalentes, pero el más usado y simple es el *primero*.

-----------------------------------------------------------
**indices en un Array**

A cada elemento dentro del *array* le corresponde un índice.

var marcas = ["BMW","Peugeot","Chebrolet","Subaru","Nissan"];

Tener en cuenta que el índice del array comienza en 0, no en 1.

Esto varía segun cada lenguaje. Los que comienzan en 0 suelen conocerse como zero-index array.

-----------------------------------------------------------
**Acceder a un elemento de un Array**

> ``var marcaPreferida = marcas[2];``

-----------------------------------------------------------
**Agregar un elemento a un Array**

> ``marcas[5] = "Volvo";``

-----------------------------------------------------------
**Largo de un Array**

> ``console,log(marcas.length);``











