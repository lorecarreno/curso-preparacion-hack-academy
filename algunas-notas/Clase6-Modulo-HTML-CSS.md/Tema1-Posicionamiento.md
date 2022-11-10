CSS - position

Nos permite mover los elementos de su ubicacion inicial a otra.

- position es una propiedad de CSS utilizada para establecer el tipo de posicvionamiento deun elemento.

- El valor por mdefecto es static.

- Tambien puede tomar los siguientes valores: absolute, relative, fixed, initial, inherit.

Cuando usamos la propiedad position, primero se define un ehe de coordenadas (usando los valores absolute, relative o fixed) y luego se establece la posición del elemento respecto a dicho eje.

----------------------------------------------------------------
*position: fixed*

El *elemento se posiciona con respecto a la ventana* del browser. Provoca que el elemento quede *fijo* (no se mueve) al hacer scroll. Es necesario especificar las coordenadas del elemento con top, bottom, left y/o right.

----------------------------------------------------------------
*position: static*

Dejar posicionado un elemento de forma natural, según el orden en el codigo.

El elemento se posiciona segun el orden el el código. El valor de *static* es el valor por defecto.

----------------------------------------------------------------
*position: relative*

Posicionar un elemento con respecto a su posición natural. 

El *elemento se posiciona con respecto a su posición natural*. Es necesario especificar las *coordenadas* del elemento con top, bottom, left y/o right., de lo contrario es equivalente a static.

----------------------------------------------------------------
*position: absolute*

Posicionar nu elemento con respecto a su padre.

El *elemento se posiciona con respecto a su primer ancestro no-static*. Es necesario especificar las *coordenadas* del elemento con top, bottom, left y/o right, de lo contrario es equivalente a *static*.


