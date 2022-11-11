***Tema 2 - Etiqueta label, input y button***

----------------------------------------------------------------
**Formulario HTML -input**
----------------------------------------------------------------

Para agregar un *campo de texto* se utiliza el elemento ``<input>``

Como en un formulario pueden haber varias etiquetas *input*, se hace necesario identificar a las mismas con el atributo.

> ``<form>`` <br>
> `` <label for="email">Email:</label>`` <br>
> `` <input id="email" type="text" name="email" placeholder="Ingresar Email...">`` <br>
> `` <button type="submit">Enviar</button>`` <br>
> ``</form>`` <br>

Los elementos ``<input>`` tienen un atributo *type* el cual permite definir el tipo del campo de texto.

> - text: Textos cualquiera.<br>
> - number: Números.<br>
> - email: Correos electrónicos.<br>
> - date: Fechas.<br>
> - tel: Número de teléfono.<br>
> - radio: Campos de tipo radio, solo se puede elegir una opción.<br>
> - checkbox: Para campos de selección múltiple.<br>

