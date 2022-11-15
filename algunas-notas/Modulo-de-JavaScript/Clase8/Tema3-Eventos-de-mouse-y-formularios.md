-----------------------------------------------------------
<h1>Eventos del mouse</h1>


-----------------------------------------------------------
*Evento onclick*

Se utiliza *onclick* para crear un *evento* cuando el usuario haga *click* sobre un elemento de la web. Ejemplo:

En archivo HTML:

> ``<button type="text" class="clear" onclick="clear()"> Limpiar </button>``

En archivo JS:

> ``funciton clear() {`` <br>
> ``    document.querySelector(".clear").value = "";`` <br>
> ``}`` 


-----------------------------------------------------------
*Eventos del mouseOver*

Es una acción que se dispara al pasar el mouse por *encima* del elemento al que le seteamos el evento.

Ejemplo:

> ``texto.addEventListener("mouseover", function (){`` <br>
> ``    console.log("pasaste el mouse";`` <br>
> ``})`` 

Otra forma de hacer lo mismo:

> ``let texto = document.querySelector(".text");`` <br>
> ``texto.onmouseover = function(){`` <br>
> ``    console.log("pasate el mouse");`` <br>
> ``}`` 


-----------------------------------------------------------
<h1>Eventos del formulario</h1>

-----------------------------------------------------------
*Evento onblur*

Se utiliza *onblur* para crear un evento cuando el usuario retira el foco de un elemento. Es uno de los más utilizados con respecto a la validación de formularios.

En archivo HTML:

> ``<input type="text" id ="name" onblur="blurFuntion();"> Name </input>``

En archivo JS:

> ``funtion blurFuntion() {`` <br>
> ``    var nameInput = document.getElementById("name");`` <br>
> ``    nameInput,value = nameInput.value.toUpperCase();`` <br>
> ``}`` 


-----------------------------------------------------------
*Evento onfocus*

Se utiliza *onfocus* para crear un evento cuando el usuario se pare sobre un elemento de la web. Ejemplo:

En archivo HTML:

> ``<input type="text" id="name" onfocus="focusFunction(this)"> Name </input>``

En archivo HTML:

> ``function focusFunction (x) {``<br>
> ``    x.style.background="orange";``<br>
> ``}``

-----------------------------------------------------------
*Evento onsubmit*

Se utiliza *onsubmit* para crear un evento cuando el usuario presiona el botón enviar de un formulario. Ejemplo:

En archivo HTML:

<form method="post" action="/" onsubmit="submitFunction()">...</form>

En archivo JS:

> ``function submitFunction() {`` <br>
> ``    //preceso para el envío del formulario`` <br>
> ``}`` 


