***Variables***

----------------------------------------------------------------
**Variables (1/5)**

Son contenedores que permiten guardar información (valores) para poder usarla más tarde.

----------------------------------------------------------------
**Variables (2/5)**

Para definir una variable en JavaScript y asignarle un valor, debemos utilizar la palabra reservada var, seguida del nombre de la variable, y por último el operador = para asignar el valor deseado.

> ``var precio = 100;``

----------------------------------------------------------------
**Variables (3/5)**

> ``var precioA = 100;`` <br>
> ``var precioB = 50,5;`` <br>
> ``var precioA = precioA + precioB;`` <br>
> ``var precioC;`` <br>

La línea 1: Sentencia que *declara* una variable llamada precioA y le *asigna* el valor 100.

La línea 2: Sentencia que *declara* una variable llamada precioB y le *asigna* el valor 50.5.

La línea 3: Sentencia que *asigna* la suma de precioA + precioB a la variable precioA.

La línea 4: Sentencia que *declara* una variable llamada precioC.

----------------------------------------------------------------
**Variables (4/5)**

Las variables pueden guardar el resultado de *expreciones*.

> ``var unNumero = 5+7;`` <br>
> ``var unString = "Hola" + " " + "Mundo";``

- Importante: no se guardan las expresiones en  sí mismas, lo que se guarda es el resultado.

----------------------------------------------------------------
**Variables - Cómo se nombran? (5/5)**

- Comenzar los nombres con letras.

- Sólo usar letras y números.

- NO usar espacios.

- Recordar que los nombres son *case sensitive* (hola y Hola son distintos).

- *Evitar palabras reservadas* (palabras que ya son usadas por JS).<br>
Ej: una variable no se puede llamar var ni typeof.

- Usar nombres mnemoténicos (descriptivos) (Ej: es mejor usar precioTotal que x1).

- Es común usar *camelCase* (Ej: precioVariableTotal en lugar de preciovariabletotal).

- Es común (y recomendable) usar nombres en inglés.
