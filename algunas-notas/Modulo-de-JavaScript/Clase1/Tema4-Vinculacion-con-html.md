Similar a lo que sucede con CSS, hay varias maneras de agregar código JS a nuestras páginas HTML.

----------------------------------------------------------------
**Dónde ponemos nuestro código JS (1/3) - Método 1**

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/js-metodo1.png?raw=true)

----------------------------------------------------------------
**Dónde ponemos nuestro código JS (2/3) - Método 2**

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/js-metodo2.png?raw=true)

----------------------------------------------------------------
**Dónde ponemos nuestro código JS (3/3)**

Si pusiéramos el código JS al inicio del documnto HTML, el HTML no se cargaría (y no se mostraría hasta que primero se haya cargado el JS).

Dependiendo del tamaño del JS el usuario podria incliso ver la pagina en blanco por unos segundos.

Además, en caso de que el código JS tuviese la intención de modificar algo de la página, si el JS se ejecutase al principio, tendria no tendría nada que modificar, Es decir, el JS on puede modificar alfo que aún no existe".

Por eso en general, lo recomendable es colocar el JS al final del cocumento HTML (justo antes del tag ``</body>`` que cierra).

----------------------------------------------------------------
