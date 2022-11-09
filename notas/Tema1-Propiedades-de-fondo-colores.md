***Tema 1 - Propiedades de fondo COLOR (porque también hay de imágenes)***

Uno de los primero cambios de estilo que hacemos cuando aprendemos CSS es hacer variaciones en los colores de *primer plano* y de *fondo* de un documento HTML o de cualquiera de sus elemementos o partes.

Sin embargo, indicar el color específico no es tarea fácil. 

Hay múltiples formas de definir un color en CSS, algunas más sencillas, otras más complejas.

La propiedad CSS que podemos utilizar para cambiar el color de fondo de un elemento HTML es:

> ``selector{``
> ``    background-color: #DDE0E3;`` <br>
> ``}``

------------------------------------------------

**Formas de indicar el color**

Todas las propiedades CSS donde existen valores, establecen la posibilidad de indicar varias *formas alternativas* (con algunos derivados) para especificar el color deseado:

- Función RGB : utiliza una función rgb() (rojo, verde, azul).

- Código RGB hexadecimal: Notación RGB abreviada en hexadecimal.

- Función HSL: Función hsl() (matiz de color, saturation y brillo).

------------------------------------------------
**Palabras clave de color**

El primer caso (y más limitado) permite establecer el color utilizando palabras reservadas de colores, como red. blue, orange, white, navy, yelow u otras.

Existen más de 140 palabras clave para indicar colores.

Un ejemplo de esto sería:

> ``selector {`` <br>
> ``    background-color: blue;`` <br>
> ``}`` <br>

------------------------------------------------
**Funcion RGB**

Si queremos indicar en CSS un color utilizando la función RGB, podemos utilizar la *función rgb()*, escogiendo entre una de las siguientes variaciones:

- rgb(r,g,b) *Notación clásica*: Valores numéricos o pocentajes separados por una coma.
- rgb(r,g,b,a) Se añade al anterior un valor correspondiente al canal alfa, separado por una coma.
- rgb(r g b) *Notación moderna*: Valores numéricos o porcentajes separados por un espacio.
- rgb(r g b / a) Se añade al anterior un valor correspondiente al canal alfa, separado por /

**Función RGB** (2/2)

Como se puede ver, en cada uno de los casos anteriores, se deben indicar los valores r, g y b.
Significan rojo, verde y azul, respectivamente, y hacen referencia a la cantidad de color que poseen estos canales para generar otro color. Para especificarlo se puede hacer de dos formas:
- Como números, desde 0 al 255, siendo el primero más ocuro y el ultimo más claro.

- Como porcentajes, desde 0% al 100%, siendo el primero el más oscuro y el segundo el más claro.