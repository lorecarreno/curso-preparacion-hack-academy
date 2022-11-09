Los selectores se utilizan para determinar sobre qué elemento de HTML se aplicarán los estilos.

**Básicamente, hay 4 tipos de selectores:**

- element
- class
- id
- pseudo classes

***Tipos de selectores:***

*element*
> ``p{`` <br>
> ``    color: red;`` <br>
> ``}`` <br>

*class*
> ``.introduccion{`` <br>
> ``    background-color:blue;`` <br>
> ``}`` <br>

> ``.description{`` <br>
> ``    color:red;`` <br>
> ``}`` <br>

*id*
> ``#pepito{`` <br>
> ``    color:red;`` <br>
> ``}`` <br>

*pseudo classes*
> ``a:link{...}`` <br>
> ``a:visited{...}`` <br>
> ``a:hover{...}`` <br>
> ``a:active{...}`` <br>
> ``a:focus{...}`` <br>

----------------------------------------------------------------
***Jerarquia de Selectores CSS***
- Los id son mas especidficos que una clase.
- class es mas especidfico que element.
- si dos reglas son igual de especidficas la ultima gana.

