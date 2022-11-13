----------------------------------------------------------------
<h1> Sentencia IF / ELSE IF / ELSE </h1>
----------------------------------------------------------------

**Sentencia else if (1/2)**

> ``if (condicion_A)`` <br>
> ``{`` <br>
> ``    //Bloque de codigo a ejecutar si la condicion A se cumple...`` <br>
> ``}`` <br>
> ``else if (condicion_B)`` <br>
> ``{`` <br>
> ``    // Bloque de codigo a ejecutar si la condicion A no se cumple`` <br>
> ``    // y se cumple la condicion B`` <br>
> ``}`` <br>

**Sentencia else if (2/2)**

> ``if (hora > 18) {`` <br>
> ``    alert("Está cerrado, es tarde");`` <br>
> ``} else if (hora < 9) {`` <br>
> ``    alert("Está cerrado, es temprano");`` <br>
> ``} else {`` <br>
> ``    alert("está abierto);`` <br>
> ``}`` <br>

----------------------------------------------------------------
<h4> Ejercicios</h4>
----------------------------------------------------------------

- 1. Definir una función llamada esPar que reciba como paramertro un numero qualquiera y retorne true si es par. En caso contrario, retorna false.

- 2. Definir una función llamada maximoDeDos que reciba como argumentos dos numeros cualesquiera y retorne el mayor. Si los números son iguales a retornar dicho número.
Nota: no utilizar la función Math.max(...).

- 3. Definir una función llamada esFinDeSemana que reciba como argumento una cadena de texto que represente a un día de la semana y retorne true si el día es sábadp o domingo o false si es un día entre semana.