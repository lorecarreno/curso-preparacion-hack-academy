***Tema 3 - Media queries***

----------------------------------------------------------------
**Los media queries**

Son un conjunto de reglas CSS que permiten reorganizar el contenido dependiendo de las condiciones de visualización del documento.

Generalmente se escriben al final de nuestra hoja de CSS.

----------------------------------------------------------------
**Los media queries para Mobile First**

> ``@media (min-width: 1000px) {`` <br>
> ``    /* reglas de CSS */`` <br>
> ``}`` <br>

Al especificar *min-width*, se esta ordenando que si *como mínimo* hay 460px de ancho del viewport, se apliquen estas reglas de estilo. Es algo como: "desde este punto hacia arriba".