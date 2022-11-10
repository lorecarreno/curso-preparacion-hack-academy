***Tema 1 - Elementos block, inline e inline-block***

Cambian el flujo de un elemento

*display* es la propiedad de CSS que permite controlar la estructura (o layout) de una página web.

Con la propiedad *display* se puede trabajar con estos valores:

- display: block; /* setea al elemento como de tipo block*/

- display: inline; /*setea al elemento como de tipo inline*/

- display: none; /*Oculta el elemento*/

- display: inline-block; /*Similar a inline, pero puede tener widht y height*/

----------------------------------------------------------------
**Elementos de tipo Block vs. Inline** (1/2)

Por defecto, todo elemento en HTML tiene un tipo de visualización (display) predeterminado.
Los dos mas comunes son:

- **Block**: es un elemento que ocupa todo el ancho de su elemento padre (contenedor),
generando un salto de línea antes y después de si mismo.

Elementos block mas usados: <h1>, <h2>, <div>, <p>, <ul>, <ol>, <form>.

- **Inline**: es un elemento que ocupa sólo el ancho que precisa y no genera saltos de línea.

Elementos inline mas usado: <a>, <em>, <strong>, <button>, <span>.

----------------------------------------------------------------
**Elementos de tipo Block vs. Inline** (2/2)

Cosas importantes a tener en cuenta de los elementos de tipo block e inline:

- *Los elementos block* siempre aparecen *debajo* del elemento del bloque anterior. Esta es la visualización (display) "natural" dentro del documento HTML.

- El *ancho de los elementos block* se establece automáticamente en función del ancho de su contenedor padre.

- *La altura* predeterminada de los elementos de bloque se basa en su contenido interno. Pero si la ventana del navegador no es suficientemente ancha, un <h1> (por ejemplo) se divide en dos líneas de texto y su altura se ajusta en consecuencia.

- *Los elementos inline* no afectan *el espaciado vertical*.

- El *ancho de los emelentos inline* se basa en su contenido interno, no en el del elemento contenedor padre.

----------------------------------------------------------------
***Cambiando la visualización de un elemento*** 
----------------------------------------------------------------

**Cambian el flujo de un elemento**

Se puede anular el tipo de caja predeterminada de los elementos HTML con la propiedad *display*.

Por ejemplo, si se desea hacer que los elementos <em> y <strong> sean elementos en bloque, podríamos implementar una regla de la siguiente manera:

> ``em, strong{`` <br>
> ``    display: block;`` <br>
> ``}`` <br>

*display* es la propiedad de CSS que permite controlar la estructura (o layout) de una página web.

Con la propiedad *display*, se puede trabajar con estos valores:

- *display: block; /*Setea al elemento como de tipo block*/

- *display: inline; /*Setea al elemento como de tipo inline*/

- *display:  none; /*Setea al elemento*/

- *display: inline-block; /*Similar a inline, pero puede tener widht y height*/
