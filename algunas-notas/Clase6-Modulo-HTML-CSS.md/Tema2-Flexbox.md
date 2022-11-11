***Tema 2 - Flexbox***

----------------------------------------------------------------
**Flexbox (1/3)** Otra forma de armar layouts.

Flexbox no es una propiedad de CSS, sino un *conjunto de propiedades*, para poder *armar el layout* de una página. Es decir, Flexbox permite organizar elementos en la página, de forma horizontal y vertical.

El primer borrador de la *especificacion de Flexbox* se publicó en julio 2009. Desde setiembre 2012 hasta el día de hoy, la especificacion se encuentra en "candidate recommendation", lo cual significa que su bien no es definitiva, es estab;e y se encuentra *muy soportada por los navegadores*.

----------------------------------------------------------------
**Flexbox (2/3)**

Flexbox es muy *poderoso*, pero también es *algo complejo*.

Tiene tantas opciones de configuración, que se podría hacer un sólo de Felxbox. De hecho, hay uno muy bueno y gratuito hecho por Wes Bos:

[https://flexbox.io](https://flexbox.io) En este curso nos limitaremos a hacer una breve introduccion al tema.

Para aprender más: [🐸FlexboxFroggy](https://flexboxfroggy.com/)

----------------------------------------------------------------
**Flexbox (3/3)**

La idea de Flexbox es: Dado un elemento padre (al cual se lo llamará *flex container*) posicionar sus elementos hijos (a los cuales se los llamará *flex items*).

![Ejemplo1](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/flexbox-ej-1.png?raw=true)

En este ejemplo, se establece que el *flex container* se comporte como una row, y por lo tanto, los flex items se comportan como columnas. La primera de ancho 1/3 y la segunda 2/3. (1 hace referencia a que la caja sidebar va a tomar un tercio del tamaño total y el flex 2 hace referencia a que la caja va a tomar 2 tercios del tamaño total. Sin embargo se puede implementar un tamaño porcentual widht 50%, widht 40% etc.)

----------------------------------------------------------------
**Flexbox Flex Direction**
----------------------------------------------------------------

Por defecto, los flex items se posicionan en fila. Se dice que el eje principal (main axis) es el horizontal. 

Sin embargo, Flexbox permite cambiar el eje principal (hacerlo vertical) y posicionar los flex items en columna, usando la propiedad flex-direction.

----------------------------------------------------------------
**Flexbox Alineación vertical (1/2)**
----------------------------------------------------------------

Alinear elementos de forma vertical siempre fue algo complicado en CSS, sobre todo si las alturas varían. Gracias a Flexbox, este problema se resuelve muy fácilmente.

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/alineacion-vertical1-2.png?raw=true)

----------------------------------------------------------------
**Flexbox Alineación vertical (2/2)**
----------------------------------------------------------------

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/alineacion-vertical2-2.png?raw=true)

----------------------------------------------------------------
**Flexbox -Justify Content & Align Items**
----------------------------------------------------------------

