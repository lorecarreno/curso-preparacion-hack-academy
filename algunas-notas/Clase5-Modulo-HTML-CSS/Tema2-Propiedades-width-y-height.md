***Tema 2 - Propiedades width y height***

----------------------------------------------------------------
**widht* : ancho de un elemento (1/2)**

Todos los elementos HTML de un tipo *block* (e inline-block) pueden recibir valores que modifiquen su *ancho*. Para ello existe la propiedad CSS *widht*:

> ``.cabecera {`` <br>
> ``    width: 500px;`` <br>
> ``}`` <br>
> `` `` <br>
> ``.sidebar {`` <br>
> ``    widht: 75%;`` <br>
> ``}`` <br>

El valor numérico que recibe la propiedad *widht* puede estar expresado en distintas unidades de medida como pixeles (px), porcentaje (%), rem, vw, etc.

----------------------------------------------------------------
**widht* : ancho de un elemento (2/2)**

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/ancho-de-un-elemento.png?raw=true)

En este ejemplo el elemento contenedor ocupa 1200px de ancho, la cabacera ocupará 500px mientras el Sidebar tendra el 75% de ancho que tiene el elemento contenedor. Si el elemento contenedor llegara a cambiar su dimensiones de ancho, la cabecera mantendrá su tamaño pero el sidebar si cambiaría.

El widht únicamente lo reciben los elementos de tipo block. Si se aplica widht a un elementos de tipo inline no va a funcionar. -Por eso es que CSS nos da la propiedad display para que le pongamos a un elemento de tipo inline un display-block o un display-inline-block, los elementos de tipo inline-block si tienen la posibilidad de aceptar el width.

----------------------------------------------------------------
**heigth* : alto de un elemento (1/2)**

Todos  los elementos HTML de tipo *block* (e inline-block) pueden recibir valores que modigfiquen su alto. Para ello existe la propiedad CSS *heigth*:

> ``.contenedor{`` <br>
> ``    heigth: 300px;`` <br>
> ``}`` <br>

Importante: en general, no se recomienda aplicar heigh a no ser que sea estrictamente necesario.

Esto se debe a que, por lo general, el contenido de las cajas es variable, particularmente cuando se trata de texto. Por lo tanto para permitir que las cajas se adapten a su contenido, se les asigna un alto fijo que se deja libre.

----------------------------------------------------------------
**heigth* : alto de un elemento (2/2)**

El problema que puede ocurrir al aplicar *height* a un elemento, es que su su contenido supera el tamaño definido en *height*, dicho contenido se desborda, obteniendose un resultado visual indeseado que se conoce como *overflow*.

----------------------------------------------------------------
***Algunos comentarios importantes***

- Las propiedades widht y height solamente se pueden aplicar a elementos de tipo block (o inline-block).

- la propiedad width puede recibir valores en px, %, re,, vw, etc.

- La propiedad height se usa poco, ya que la misma podría generar overflow del contenido.

- Por defecto todos los elementos de HTML tienen un valor de widht llamado auto, que indica que el navegador les asignará un tamaño específico. Para un elemento de tipo block, el tamaño auto significa que dicho elememento ocupará todo el ancho de su padre.

- Por defecto todos los elementos de HTML tienen un valor de height llamado auto, que indica que el navegador les asignará un tamaño que será igual al contenido interno del elemento.







