<h1>Consumiedo APIS</h1>

**Ajax**

- AJAX = Asynchronous JavaScript and XML.

- Es una *técnica* que permite *interactuar* (enviar y recibir información) con un servidor sin necesidad de recargar la página.

- Su surgimiento a mediados de la década del 2000 significó un cambio enorme para JavaScript y el desarrollo de aplicaones web.

- Permitió la creación de aplicaciones como Gmail, Google Maps, Facebook, Twitter, etc. Single Page Applications (SPA) que se parecen a aplicaciones de escritorio.

----------------------------------------------------------------
**Qué se puede recibir del servidor mía AJAX?**

Cualquier cosa, pero en general:

- texto plano (texto sin un formato especifico)

- HTML

- JSON (que sustituyó a XML; igual se le sigue llamando AJAX).

----------------------------------------------------------------
**Qué se puede recibir del servidor mía AJAX?**

Realizar llamadas HTTP con JavaScript:

----------------------------------------------------------------
**Realizar llamadas HTTP (1/4)**

Antiguamente, la forma de realizar llamadas HTTP con JavaScript era utilizando la funcionalidad XMLHttpRequest.

Sin embargo, su dificultad de uso motivó a que en 2015 se implementase una nueva forma de realizar este tipo de llamadas usando la funcion *fetch* (nativa de JS).

👉 También existen librerias externas que cumplen la misma funcionalidad como, por ejemplo, Axios (que es popular e incluye algunas ventajas).

----------------------------------------------------------------
**Realizar llamadas HTTP (2/4)**

Ejemplo de uso de función *fetch*:

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/consumiendo-API-funcion-fetch.png?raw=true)

La sintáxis de la función *fetch* suele ser complicada de entender para quien está iniciando, dado que está basada en el concepto de *promesas* de JavaScript. A continuación se realizará una explicación básica y lo más sencilla posible, contemplando los concimientos teóricos que disponemos al día de hoy.

----------------------------------------------------------------
**Realizar llamadas HTTP (3/4)**

Explicación de la función *fetch*:

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/explicacion-funcion-fetch,png.png?raw=true)

1. La función *fetch* recibe como parámetro un string con la URL a donde se desea realizar el llamado HTTP. A modo de simplificación, este código estádiciendo: "Quiero obtener los datos que se encuentran en esta dirección".

2. El primer *then* es una función qye se ejecuta cuando la llamada HTTP haya *finalizado* y se hayan recibido los datos (en este caso datos en formato JSON). La función *json* convierte el JSON recibido (que es un string)
a un objeto de JavaScript.

3. El segundo *then* se utiliza al final del proceso (si es que el prceso fue exitoso). Aquí se indica qué se debe reaizar con los datos recibidos. Aquí el parámetro *data* es un objeto Javascript y será la información final con la que vamos a trabajar.

4. Opcionalmente, se puede definir una función *catch* que se ejecuta en caso de que haya ocurrido un error en el proceso.

----------------------------------------------------------------
**Realizar llamadas HTTP (4/4)**

Probar de realizar una llamada HTTP (puede ser desde la consola del navegador) y observar la pestaña network en las Developer Tools.

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/network-devtools.png?raw=true)













