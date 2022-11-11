***Tema 2 - Sistema de grillas***

----------------------------------------------------------------
**Bootstrap - Grid System (1/10)**

El grid system de Bootstrap es un sistema de filas y columnas que permite armar el layout de nuestra página de una forma sencilla.

Las filas y columnas no son más que divs con ciertos estilos CSS.

*Importante* La clase .row y .col las provee bootstrap. No las tenemos que crear nosotros.

----------------------------------------------------------------
**Bootstrap - Grid System (2/10)**

Para agregar una columna, sólo hace falta agregar otro elemento <div class="col">.

Se pueden agregar tantas columnas como se quiera.

----------------------------------------------------------------
**Bootstrap - Grid System (3/10)**

Bootstrap también permite definir el ancho de una columna.

Tener en cuenta que la suma de los anchos no puede superar 12. (*máxima cantidad de columnas en row*)

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/bootstrap-suma-de-anchos.png?raw=true)

> ``<div class="row">`` <br>
> ``    <div class="col-4">`` <br>
> ``        ...`` <br>
> ``    </div>`` <br>
> `` `` <br>
> ``    <div class="col-8">`` <br>
> ``        ...`` <br>
> ``    </div>`` <br>
> ``</div>`` <br>

----------------------------------------------------------------
**Bootstrap - Grid System - Reglas (4/10)**

- Toda columna debe ir inmediatamente dentro de una fila. Adentro de una fila, sólo se puden ponre columnas.

- Nustro contenido se agrega dentro de las columnas (jamas dentro de las filas).

- Dentro de las columnas incluso se pueden agregar otros ``<div>``.

----------------------------------------------------------------
**Bootstrap - Grid System - Reglas (5/10)**

Otras reglas:

    - al utilizar columnas con anchos predefinidos, recordar que la suma de anchos de las columnas de una fila debe ser menos a 12.

    - en general, evitar cambiar los estilos de las filas y columnas (no cambiar el float, position, display, margin ni padding).

    - en caso de necesitar layouts más complejos, es posible agregar filas adentro de columnas. Esto se conoce como anidación o nesting.

----------------------------------------------------------------
**Bootstrap - Grid System - Containers (6/10)**

- Bootstrap nos da un elemento que se llama container, nos permite usar el contenedor para delimitar el tamaño de las columnas.

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/bootstrap-container.png?raw=true)

----------------------------------------------------------------
**Bootstrap - Grid System - Containers (7/10)**

- Para que las filas no toquen los bordes de la página y para que queden centradas en la misma, es común colocarlas inmediatamente adentro de divs con clase .container (ancho fijo) o .container-fluid (ancho 100%).

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/bootstrap-grid-system-containers.png?raw=true)

----------------------------------------------------------------
**Bootstrap - Grid System - columnas responsive (8/10)**

- No siempre se querrá que las columnas se vean tanto en mobile como en desktop. A veces querrá modificar el comportamiento de las mismas según el tamaño de la pantalla. Por ejemplo, 4 columnas en mobile suelen quedar demasiado apretadas y suele ser mejor mostrarlas apiladas (una sobre otra).

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/bootstrap-columnas-responsive.png?raw=true)

----------------------------------------------------------------
**Bootstrap - Grid System - columnas responsive (9/10)**

Usando los tamaños sm, md, lg, xl y xxl, se le puede indicar a ;as cp;umnas a partir de qué tamaño de pantalla deberán funcionar.

En el ejemplo las dos columnas solo se verán a partir de pantallas medium en adelante, es decir, mayores o iguales a 768px.

Para pantallas más chicas, los <div> se verán apilados.

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/bootstrap-grid-system-columnas-responsive.png?raw=true)

----------------------------------------------------------------
**Bootstrap - Grid System - Responsive breakpoints (10/10)**




