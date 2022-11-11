***Tema 1 - Introducción a Bootstrap***

----------------------------------------------------------------
**Que es un Framework**

Un framework es un conjunto de codigo pre-escrito por alquien mas, que se puede reutilizar para acelerar nuestro trabajo.

Generalmente, en el framework se resuelven problemas comunes con los que se enfrentan los desarrolladores día a día.

Es importante saber cuándo utilizar un framework y cuando no.

**Una libreria rambién es un conjunto de código reutilizable. La diferencia está en el control que tiene el programador sobre su código. Al utilizar un framework el programador pierde el control porque el framework 'le exige' que se las cosas se hagan de determinada manera. Al utilizar una libreria, el programador tiene más control sobre qué usar y qué no y sobre todo sobre cómo quiere que funcione su aplicación.**

----------------------------------------------------------------
**Frameworks CSS -Bootstrap**

Existen varios frameworks de CSS.

El más popular y el que vamos a usar en el curso es Bootstrap:

> - Creado por empleados de Twitter en 2011.<br>
> - Es open-source.<br>
> - Es un framework CSS (aunque también trae algunas utilidades Java Script).<br>
> - Sólo para la parte de CSS contiene aprox. 10000 líneas de código!<br>
> - [Documentacion](https://getbootstrap.com).<br>

----------------------------------------------------------------
**Bootstrap - Versiones**

En diciembre de 2020 salió la versión 5 de Bootstrap y es la que utilizaremos en este curso.

La versión 5 no soporta Internet Explorer.

Si se necesita compatibilidad con navegadores más antiguos, se puede usar la versión 4 que funciona a partir de IE10 o la verión 3 que funciona a partir de IE8.

- Al consultar una documentación verificar qué versión se está consultando.

----------------------------------------------------------------
**Bootstrap - Ventajas (1/2)**

- Grid System: Funcionalidad que permite estructurar una página (armar el layout)
de una forma muy sencilla (sin tener que usar prppiedades CSS complicadas).

- CSS Reset/Reboot: Funcionalidad que elimina (resetea) todos los estilos que los navegadores setean por defecto. Por ejemplo: se setean los márgenes del body en 0 (cero).

- Responsive Design: Funcionalidad que ajusta de forma automática el diseño de nuestras páginas según el tamaño de pantalla del dispositivo utilizado.

- Facilidad de uso: Bootstrap es un framework muy sencillo de utilizar.

----------------------------------------------------------------
**Bootstrap - Ventajas (2/2)**

- Mobile first: Bootstrap promueve que las páginas se diseñen pensando, en primera instancia, en dispositivos móviles. Es decir, al diseñar un sitio lo primero que deberíamos preguntarnos es cómo se ve un celular y luego preguntarnos como se ve en un notebook/desktop.

- Comunidad de usuarios: Bootstrap cuenta con una gran comunidad de usuarios que están continuamente mejorando el frameworks. Al ser tan popular, facilita el trabajo con otros desarrolladores ya que probablemente todos hayan usado Bootstrap en algún momento.

- Documentación: Es clara, fácil de consultar y tiene buenos ejemplos.

- Estilo y componentes: Bootstrap trae un montón de estilos y componentes pre hechos que permiten una rápida prototipación. 

----------------------------------------------------------------
**Bootstrap - Desventajas**

- Puede ser muy pesado para un sitio simple y pequeño.

- La parte de CSS pesa 153kB y la parte de JavaScript pesa 81kB. Esto significa que al comenzar a usar Bootstrap, nuestro sitio ya pesa 234kB aún sin haber escrito ni una sola línea de código.

- Sitios web creados usando Bootstrap pueden quedar demasiado parecidos entre sí y por tanto no destacar.

----------------------------------------------------------------
**Bootstrap - Instalación -Método 1**

- Descargar Zip de: [https://getbootstrap.com/docs/5.1/getting-started/download/](https://getbootstrap.com/docs/5.1/getting-started/download/)

- Descomprimir el ZIP y colocar el archivo bootstrap.min.css en la carpeta CSS de nuestro proyecto.

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="widht=device-widht, initial-scale1">
    ...
    <link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
    ...
</head>

En este ejemplo se puede ver el archivo de Bootstrap instalado en carpeta css del proyecto. En una ruta relativa.

----------------------------------------------------------------
**Bootstrap - Instalación -Método 2**

- Ingresar a: [https://getbootstrap.com/docs/5.1/getting-started/introduction/#quick-start](https://getbootstrap.com/docs/5.1/getting-started/introduction/#quick-start)

- Copiar la linea de código que dice ``<link>`` y pegarla en el ``<head>`` de la página HTML.


----------------------------------------------------------------
**Bootstrap - Instalación -Método 1 vs Método 2**
----------------------------------------------------------------

*Metodo 1*: - Alojar archivo CSS de Bootstrap en nuestra carpeta CSS.

- Lleva más tiempo e instalarse (hay que bajar archivos y colocarlos en la carpeta correcta). 😥

- Nuestro sitio no depende de un sitio externo para fuincionar. 😀

- Nuestro sitio no precisa de internet para fuincionar. 😄


*Metodo 2*: - Linkear a archivo CSS de Bootstrap en servidor externo (CDN).

- Es más rápido de instalar (no hay que descargar nada, sólo copiar y pegar una línea de código). 😃

- Si el servidor externo se cae, nuestro sitio no se verá bien. 😥

- El sitio precisa de internet para fuincionar 😥

- Suele cargarse más rápido. 😄

----------------------------------------------------------------
----------------------------------------------------------------
> En la documentación está el saber.