
**Familia tipografica**

propiedad *font family*

>``selector {`` <br>
>``    font-family: "Helvetica Neue", Helvetica, sans-serif;`` <br>
>``}`` <br>

***Propiedades CSS***

**Tamaño tipografico**

*font-size* (usando px)

- La unidad de px permite establecer el tamaño del tecto en píxeles.

- Al usarla el tamano del texto queda fijo (independientemente del tamaño de los demas textos de la página o del tamano por defecto del browser).

- Es la unidad mas fácil de usar pero no siempre la mas recomendada.

*font-size* (usando em)

Esta unidad permite establecer el tamaño de un texto de forma *relativa* al tamaño del texto del elemento actual.
Ejemplo: 2 em significa que el texto será 2 veces más grande qye el texto actual.

*font-size* (usando %)

Similares características a em, pero se especifica como un porcentaje. Puede ser utilizado en conjunto con otras unidades.
En general, 1 em = 100%.

*font-size* (usando rem)

Esta unidad permite establecer el tamaño de un texto de forma relativa al tamaño del texcto establecido en el root, es decir, en ``<html>``, que en general es de 16px (en la mayoría de los browsers).

Esto hace que rem sea más "controlable" que em ya que todos los tamaños dependen directamente del tamaño definido en el root, en lugar del tamaño definido en el elemento en cuestión.
👉Esta es la *unidad que se recomienda usar* para textos.

