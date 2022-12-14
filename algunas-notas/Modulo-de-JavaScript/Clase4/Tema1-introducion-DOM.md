<h1>Introducción al DOM</h1>

----------------------------------------------------------------
**Que es DOM**

- DOM = Document Object Model.

- Cuando se carga un página el browser crea un DOM de la página a partir del HTML. Es una representación del documento que tiene una estructura jerárquica con forma de árbol.

- DOM ≠ HTML

- DOM ≈ ­­­El codigo que se ve en dev tools.

- JavaScript permite modificar el DOM pero no modificar el HTML.

----------------------------------------------------------------

*Objeto window*

Escribir en consola:

``window;``

EL objecto window representa la ventana abierta del navegador. Tambien se le llama BOM (Browser Object Model) y permite que JavaScript interactue con toda la ventana, no solo con el documento HTML.

Esto permite hacer consultas, como por ejemplo, obtener el ancho de ventana (incluyendo la scrollbar) o informacion de la ubicacion (URL);

``window.innerWidth;`` <br>
``window.location;``


*Objeto document*

Escribir en consola:

``document;``

El objeto document es una referencia al documento HTML dentro de la ventana.

Es el objeto con el que vamos a interactuar más frecuentemente.

Es quien nos permite acceder y modificar el DOM.

Nota: Tambien se puede acceder a document de esta forma:

``window.document;``

----------------------------------------------------------------
**Arbol de nodos (1/2)**

DOM transforma todos los documentos HTML en un conjunto de elementos llamados *nodos*, que están interconectados y que representan los *contenidos* de las páginas web y las *relaciones* entre ellos. Por su aspecto, la unión de todos los nodos se llama "árbol de nodos".

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/js-arbol-de-nodos.png?raw=true)

----------------------------------------------------------------
**Arbol de nodos (2/2)**

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/js-arbol-de-nodos2.png?raw=true)

Como podemos ver, el documento completo está contenido en un elemento html. Este elemento directamente *contiene* otros dos: *head* y *body*. Estos se muestran en el modelo como sus hijos, y ellos apuntan hacia html como su padre. Y así continúa, bajando a través de la jerarquía del documento, en el que cada elemento apunta a sus descendientes directos como hijos, y a su ancestro directo como su padre.

