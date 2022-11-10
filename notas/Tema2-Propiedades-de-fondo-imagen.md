***Tema 2 - Propiedades de fondo (imágenes)***

Es posible que buscando hacer un diseño mas avanzado, en lugar de utilizar un color de fondo quieras utilizar imagenes.

Para ello, CSS te proporciona la propiedad *background-image*, con la cual podemos indicar imágenes de fondo.

En el caso de querer utilizar *imágenes de fondo*, como ya hemos dicho, utilizaremos la propiedad background-image y en el valor, el nombre de la imagen (o la direccion URL donde está alojada), siempre rodeada del tecto url() de la siguiente manera:

> ``selector {`` <br>
> ``    background-image: url("images/bg.png")`` <br>
> ``}`` <br>

------------------------------------------------
**Opciones de imagen de fondo**

Una vez establecida una imagen de fondo con *background-image*, se puede personalizar la forma en la que se mostrará dicha imagen mediante propiedades como *background-repeat*, *background-attachment* o *background-position*, entre otras:

- *background-repeat*:     Establece el modo en el que se repite la imagen de fondo de ser muy pequena.

- *background-attachment*: Indica si la imagen de fondo permanece fija o se desplaza al hacer scroll.

- *background-position*:   Establece una posicion para la imagen de fondo, de modo que podemos moverla de sitio.

- *background-clip*:       Modo de relleno de la imagen de fondo. (Ver tema de modelo de cajas)

- *background-origin*:     Origen de la imagen de fondo si se utiliza background-clip. (Ver tema de modelo de cajas)

- *background-size*:       Establece un tamaño diferente a la imagen de fondo.

------------------------------------------------
**Propiedad background-repeat**

La propiedad background-repeat especifica si la imagen se repetirá horizontalmente(*repeat-x*), si se repetirá verticalmente(*repeat-y*), si lo hara en ambas direcciones(*repeat*) o en ninguna(*no-repeat*).

Por defecto, si no se indica nada, esta propiedad está ajustada en *repeat*.

- *repeat*:    Repite la imagen de fondo horizontal y verticalmente.

- *repeat-x*:  Repite la imagen de fondo horizontalmente (eje x).

- *repeat-y*:  Repite la imagen de fondo sólo verticalmente (eje y).

- *no-repeat*: La imagen de fondo no se repite.

------------------------------------------------
**Propiedad background-attachment**

La propiedad background-attachment especificará si la imagen de fondo seguirá el desplazamiento del uruario al hacer scroll por la página, es decir, si el usuario al hacer scroll y bajar para ver el contenido de la página, la imagen de fondo se desplazará hacia arriba siguiendo el flujo normal de una página.

Este comportamiento se consigue con al opcion scroll, que es la que viene establecida por defecto.

- *scroll*: Cuando hacemos scroll la imagen de fondo *se desplaza*.

- *fixed*: Cuando hacemos scroll, la imagen de fondo permanece *fija*.

------------------------------------------------
**Propiedad background-size (1/2)**

Un propiedad muy interesante es *background-size*, la cual nos permite dar un tamaño a la imagen de fondo. Podemos ajustar tanto el tamaño de ancho como el de alto, e incluso tenemos algunas palabras clave predefinidas para obtener un resultado específico.

- size : 1 parámetro. Aplica un (de ancho x auto) a la imagen de fondo. Mantiene la proporción.

- size size : 2 parámetros. Aplica un (de ancho x auto) a la imagen de fondo. Hay que vigilar la proporcion.

------------------------------------------------
**Propiedad background-size (2/2)**

Hay que tener en cuenta que con background-size puedes utilizar los siguientes valores:

- *auto* : No escala la imagen. Utiliza el tamaño original. Es el valor por defecto.

- *unidad* : Indicamos el tamaño específico que queremos usar (pixels o porcentaje, por ej.)

- *cover* : Escala el ancho de la imagen de fondo al ancho del elemento.

- *contain* : Escala el alto de la imagen de fondo al alto del elemento.


