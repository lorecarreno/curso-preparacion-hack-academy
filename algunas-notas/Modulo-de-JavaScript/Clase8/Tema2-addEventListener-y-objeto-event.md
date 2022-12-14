<h1>Asignaci贸n de un evento</h1>

----------------------------------------------------------------
**addEventListener**

----------------------------------------------------------------
**Detectar un evento en JavaScript (1/2)**

La funci贸n *addEventListener* permite *detectar eventos* que suceden sobre un elemento cualquiera de la p谩gina.

> ``const unElemento = document.querySelector("#elem");`` <br>
> `` `` <br>
> ``unElemento.addEventListener("nombreDEUnEvento", nombreDeUnaFunci贸n);``

馃憠 El segundo par谩metro de la funci贸n addEventListener (llamada callback)
tambi茅n se podr铆a haber declarado como una *funci贸n expresada*.

----------------------------------------------------------------
**Detectar un evento en JavaScript (2/2)**

En caso de ser necesario, es posible 'capturar' el *objeto Event* que se crea (autom谩ticamente) cuado se genera el evento. Luego se puede analizar dicho objeto.

> ``document.body.addEventListener("mousemove", function (event) {`` <br>
> ``    console.log(event);`` <br>
> ``});`` 

----------------------------------------------------------------
**Objeto event**

----------------------------------------------------------------
**event (1/3)**

Normalmente, los *manejadores de eventos* requieren informaci贸n adicional para procesar sus tareas. Si una funci贸n, por ejemplo, se encarga de procesar el evento *click*, quiz谩s necesite saber en que posici贸n estaba el rat贸n en el momento de pinchar el bot贸n.

JavaScript permoite obtener informaci贸n sobre el rat贸n y el teclado mediante un objeto epsecial llamado *event*.

----------------------------------------------------------------
**event (2/3)**

Los diferentes navegadores presentan diferencias en el tratamiento de la informaci贸n sobre los eventos. Pero de la siguiente manera, se puede obtener el objeto *event* en cualquier navegador.

> ``function manejadorEventos("elEvento") {`` <br>
> ``    var evento = elEvento || window.event;`` <br>
> ``}

----------------------------------------------------------------
**event (3/3)**

la propiedad *type* insica el tipo de evento producido, lo que es 煤til cuando una misma funci贸n se utiliza para manejar varios eventos.

*type* devuelve el tipo de evento, que es igualal nombre del mismo.

> ``var tipo = evento.type;`` 



