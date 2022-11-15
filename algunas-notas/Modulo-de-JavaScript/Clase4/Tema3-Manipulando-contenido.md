<h1>Manipulación del contenido</h1>

----------------------------------------------------------------
**Propiedades**

innerHTML/innerText


----------------------------------------------------------------
**Propiedad innerText**

Esta propiedad *innerText* permite trabajar con texto sin formato y no enriquecido.

En otras palabras, innerText recupera y establece el contenido de la etiqueta como *texto plano*.

----------------------------------------------------------------
**Propiedad innerHTML**

A diferencia de *innerText*, *innerHTML* permite trabajar con texto enriquecido html y codifica y decodifica automáticamente el texto.

En otras palabras, *innerHTML* recupera y establece el mismo contenido pero en formato HTML.

----------------------------------------------------------------
**Propiedad innerText**

Una vez que el elemento fue seleccionado, se le pueden aplicar transformaciones como, por ejemplo, cambiar el contenido:

El archivo HTML:

> ``<h2 class="subtitulo"> Hi </h2>``

En archivo JS:

> ``documento.querySelector(".subtitulo").innerText = "Hola";``

----------------------------------------------------------------
**Propiedad innerHTML**

Y, si en vez de *cambiar* el contenido, queremos *modificarlo*, sin borrar lo que estaba antes, lo podemos realizar de la siguiente manera:

El archivo HTML

<h2 class="subtitulo"> Bitcoin cierra semana de altibajos </h2>

> ``document.querySelector(".subtitulo").innerHTML += "<em>continúa inclinación a la baja</em>
