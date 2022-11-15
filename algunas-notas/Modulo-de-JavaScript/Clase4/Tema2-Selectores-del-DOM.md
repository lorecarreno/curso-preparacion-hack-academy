<h1>Selectores del DOM</h1>

----------------------------------------------------------------
**Qué se puede hacer con JavaScript y el DOM?**

- *Modificar* todos los elementos HTML en la página.

- *Modificar* todos los atributos HTML en la página.

- *Modificar* todos los estilos CSS en la página.

- *Remover*  elementos HTML y atributos.

- *Agregar* nuevos elementos HTML y atributos.

- *Reaccionar* a eventos que suceden en la página.

----------------------------------------------------------------
**Manipular el DOM con JS (1/2)**

El DOM cuenta con un monton de funciones (métodos) que permiten manipularlo.

Por ejemplo, la función ``querySelector`` permite *seleccionar* un elemento del documento (usando selectores de CSS).

> ``var titulo = document.querySelector("h1");``

Luego es posible *manipular* dicho elemento.

Por ejemplo, es posible cambiarle el texto:

> ``titulo.innerText = "Cursos de Programación";``

----------------------------------------------------------------
**Manipular el DOM con JS (2/2)**

El código anterior, también se podría haber escrito en una sola línea de código.

> ``document.querySelector("h1").innerText = "Cursos de Programación";``

Se puede probar:

> ``document.querySelector("p").style.color = "blue";``<br>
> ``document.querySelector("p").style.fontweight = "bold";``<br>
> ``document.querySelector(".row").style.border = "10px solid red";``<br>

----------------------------------------------------------------
**Función querySelector (1/3)**

La función *querySelector* retorna el *primer* elemento de la página que matchee con el selector especificado.

Si no hay ningún elemento en la página que matchee con dicho selector, la función retorna *null*.

Ejemplo:

> ``var titulo = document.querySelector("h1");``

----------------------------------------------------------------
**Función querySelector (2/3)**

Una vez que el elemento fue seleccionado, se le pueden aplicar transformaciones como, por ejemplo:

> ``var titulo = document.querySelector("h1");`` // Seleccionar el `h1` de la página. <br>
> <br>
> ``titulo.innerText = "Hola";`` // Asignarle un texto. <br>
> ``titulo.style.color = "blue";`` // Cambiarle el color de letra. <br>
> ``titulo.style.backgroundColor = "red";`` // Cambiarle el color de fondo *nótese el camelCase*. <br>

----------------------------------------------------------------
**Función querySelector (3/3)**

El archivo HTML:

<p>
loremipsum dolor sit amet, consectetur adipisicing elit. Aenean eiusmod tempor incididunt ut commodo consequat ligula eget dolor. Aenenan massa. 
</p>

El archivo CSS:

> ``.importante {`` <br>
> ``    color: red;`` <br>
> ``}`` <br>

El archivo JS:

> ``document.querySelector("p").classList.add("importante");`` 

----------------------------------------------------------------
**Función querySelectorAll (1/2)**

La función *querySelectorAll* retorna un array (lista) con todos los elementos de la página que matcheen con el selector especificado.

Si no hay ningún elemento en la página que matchee con dicho selector, la función retorna una lista vacía.

Ejemplo:

> ``var parrafos = document.querySelectorAll("p");`` 

----------------------------------------------------------------
**Función querySelectorAll (2/2)**

Dado que *querySelectorAll* retorna una lista de elementos, es necesario recorrerla para poder aplicarles alguna trnasformación.

Ejemplo:

var subtitulos = document.querySelectorAll("h2");

> ``for (var subtitulo of subtitulos) {`` <br>
> ``    subtitulo.style.color = "FF6600";`` <br>
> ``}`` <br>

