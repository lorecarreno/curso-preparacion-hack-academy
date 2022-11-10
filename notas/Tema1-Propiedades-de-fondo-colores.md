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
**Funcion RGB** (1/2)

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

> ``selector {`` <br>
> ``    background-color: rgb(255, 80, 10);`` <br>
> ``}`` <br>

------------------------------------------------
**Formato Hexadecimal** (1/2)


El *formato hexadecimal* es el más utilizado para por los desarrolladores web, y viene derivado del formato RGB.

Aunque en principio puede parecer extraño y complicado, sobre todo si no has oido hablar nunca del sistema hexadecimal (sistema en base 16 en lugar del que utilizamos normalmente: base 10), es simplemente el formato *RGB abreviado*.

Cada par de letras simboliza el valor del RGB en el sistema de numeracion *hexadecimal*.

------------------------------------------------
**Formato Hexadecimal** (2/2)

*HailPixel* nos proporciona una manera muy sencilla y rápida de seleccionar tonalidades de color en *formato hexadecimal* con solo mover el ratón.

> ``selector {`` <br>
> ``    background-color:#DDE0E3;`` <br>
> ``}`` <br>

------------------------------------------------
**Formato HSL** (1/2)

Otra cunción interesante para indicar colores en CSS es la función hsk(), ya que sus parámetros suelen ser mucho más intuitivos para la mayoría de los desarrolladores que otros como hexadecimal o RGB.

- hsl(h,s,l)   *Notación clásica*: Numero de grados separados por coma.

- hsl(h,s,l,a) Se añade al anterior un calor correspondiente al canal alfa, separado de una coma.

- hsl(h s l)   *Notación moderna*: Numero de grados separados por espacio.

- hsl(h s l a) Se añade al anterior un valor correspondiente al canal alfa, separado por /.

------------------------------------------------
**Formato HSL** (2/2)

Las siglas HSL significan matriz de color (hue), saturación y luminosidad (brillo). La primera cifra selecciona el matiz de color, representado con H en el circulo exteriro de la imagen. Se trata de un valor de 0deg a 360deg. Por otro lado, las dos siguientes, son el porventaje de saturation y el brillo del color, respectivamente, en ambos casos un valor de 0% a 100%.

- ``selector {`` <br>
- ``    background-color: hsl(120deg, 25%, 75%);`` <br>
- ``}`` <br>
