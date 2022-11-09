

----------------------------------------------------------------
**Familia tipográfica**
----------------------------------------------------------------

propiedad *font family*

>``selector {`` <br>
>``    font-family: "Helvetica Neue", Helvetica, sans-serif;`` <br>
>``}`` <br>

***Propiedades CSS***

----------------------------------------------------------------
**Tamaño tipografico**
----------------------------------------------------------------
- *font-size* (usando px)

La unidad de px permite establecer el tamaño del tecto en píxeles.

Al usarla el tamano del texto queda fijo (independientemente del tamaño de los demas textos de la página o del tamano por defecto del browser).

Es la unidad mas fácil de usar pero no siempre la mas recomendada.

- *font-size* (usando em)

Esta unidad permite establecer el tamaño de un texto de forma *relativa* al tamaño del texto del elemento actual.
Ejemplo: 2 em significa que el texto será 2 veces más grande qye el texto actual.

- *font-size* (usando %)

Similares características a *em*, pero se especifica como un porcentaje. 

Puede ser utilizado en conjunto con otras unidades.

En general, 1 em = 100%.

- *font-size* (usando rem)

Esta unidad permite establecer el tamaño de un texto de forma relativa al tamaño del texcto establecido en el root, es decir, en ``<html>``, que en general es de 16px (en la mayoría de los browsers).

Esto hace que rem sea más "controlable" que em ya que todos los tamaños dependen directamente del tamaño definido en el root, en lugar del tamaño definido en el elemento en cuestión.

👉Esta es la *unidad que se recomienda usar* para textos.

----------------------------------------------------------------
**Internlineado**
----------------------------------------------------------------
 - La propiedad *Line-height* establece la altura del interlineado.

Comunmente se usa para establecer la distancia entre lineas de texto.

El valor se puede expresar en *px* o en *em*.

 > ``selector {`` <br>
 > ``   line-height: 16px;`` <br>
 > ``}`` <br>

----------------------------------------------------------------
**Trazo**
----------------------------------------------------------------
- La propiedad *font-weight* especifica el peso o grosor de la letra.

Algunos tipos de letra sólo estan disponibles *normal* o *bold*.

> ``selector {`` <br>
> ``    font-weight: bold;`` <br>
> ``}`` <br>

----------------------------------------------------------------
**Estilo**
----------------------------------------------------------------
La propiedad *font-size* permite definir el aspecto de una familia tipográfica entre sus valores encontramos:
normal y italic.

> ``selector {`` <br>
> ``    font-style: italic;`` <br>
> ``}`` <br>

----------------------------------------------------------------
**Alineación**
----------------------------------------------------------------

- La propiedad *align* especifica la alineación horizontal del texto en un elemento.

Entre sus valores encontramos: *left*, *center*, *right* y *justify*.

> ``selector {`` <br>
> ``    text-align: center;`` <br>
> ``}`` <br>

----------------------------------------------------------------
**Decoración**
----------------------------------------------------------------
- La propiedad *text-decoration* se usa para establecer el formato de tecto a subrayado (underline),
tachado (line-through),o normal (none).

El subrayado es posicionado bajo el texto, mientras el tachado genera una línea a través de este.

> ``selector {`` <br>
> ``    text-decoration:underline;`` <br>
> ``}`` <br>

