***Tema 1 - Etiqueta form, atributos action y method***

----------------------------------------------------------------
**Formulario**
----------------------------------------------------------------

Los formularios son de los componentes mas importantes de un sitio web.

A travéz de un formulario, se captan nuevos usuarios, se captan interesados en nuestros productos (leads), se generan ventas (formularios de checkout), etc. Por eso, es sumamente importante dedicar el tiempo suficiente para *optimizarlos*, es decir, hay que trabajar para que su *conversión rate* sea el mas alto posible. 

Un formulario está determnado por el elemento ``<form>``

Dentro de este elemento, van todos los campos que el formulario vaya a mostrar al visitante.

----------------------------------------------------------------
**Formulario HTML -Envío de Email (1/2)**
----------------------------------------------------------------

Para poder enviar los datos de un formulario HTML es necesario declarar los atributos *method* y *action* para que se pueda definir con exactitud:

- Quién quieremos que procese los datos (action)

- Bajo qué protocolo vamos a enviar los mismos (method)

> ``<form method="POST" action="procesar.php">`` <br>
> `` ... `` <br>
> `` ... `` <br>
> ``</form>`` <br>

----------------------------------------------------------------
**Formulario HTML -Envío de Email (2/2)**
----------------------------------------------------------------

Pero para poder hacer un envío de nua manera sencilla (y sin tener conocimientos de Back-End), se puede usar un servicio gratuito llamado *Formspree* [https://formspree.io](https://formspree.io). El cual permite enviar los mensajes a una casilla de correo previamente definida.

- importante: nunca envíes datos confidenciales en un formulario.

> ``<form method="POST" action="https://formspree.io/numero-de-formulario-###">`` <br>
> `` ... `` <br>
> `` ... `` <br>
> ``</form>`` <br>


