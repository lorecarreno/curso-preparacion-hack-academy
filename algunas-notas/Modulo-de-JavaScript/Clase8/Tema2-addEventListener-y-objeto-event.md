<h1>Asignación de un evento</h1>

----------------------------------------------------------------
**addEventListener**

----------------------------------------------------------------
**Detectar un evento en JavaScript (1/2)**

La función *addEventListener* permite *detectar eventos* que suceden sobre un elemento cualquiera de la página.

> ``const unElemento = document.querySelector("#elem");`` <br>
> `` `` <br>
> ``unElemento.addEventListener("nombreDEUnEvento", nombreDeUnaFunción);``

👉 El segundo parámetro de la función addEventListener (llamada callback)
también se podría haber declarado como una *función expresada*.

----------------------------------------------------------------
**Detectar un evento en JavaScript (2/2)**

En caso de ser necesario, es posible 'capturar' el *objeto Event* que se crea (automáticamente) cuado se genera el evento. Luego se puede analizar dicho objeto.

> ``document.body.addEventListener("mousemove", function (event) {`` <br>
> ``    console.log(event);`` <br>
> ``});`` 

----------------------------------------------------------------
**Objeto event**

----------------------------------------------------------------
**event (1/3)**

Normalmente, los *manejadores de eventos* requieren información adicional para procesar sus tareas. Si una función, por ejemplo, se encarga de procesar el evento *click*, quizás necesite saber en que posición estaba el ratón en el momento de pinchar el botón.

JavaScript permoite obtener información sobre el ratón y el teclado mediante un objeto epsecial llamado *event*.

----------------------------------------------------------------
**event (2/3)**

Los diferentes navegadores presentan diferencias en el tratamiento de la información sobre los eventos. Pero de la siguiente manera, se puede obtener el objeto *event* en cualquier navegador.

> ``function manejadorEventos("elEvento") {`` <br>
> ``    var evento = elEvento || window.event;`` <br>
> ``}

----------------------------------------------------------------
**event (3/3)**

la propiedad *type* insica el tipo de evento producido, lo que es útil cuando una misma función se utiliza para manejar varios eventos.

*type* devuelve el tipo de evento, que es igualal nombre del mismo.

> ``var tipo = evento.type;`` 


----------------------------------------------------------------
**event (2/3)**


----------------------------------------------------------------
**event (3/3)**
