<h1>Objetos Literales</h1>

Que es un objeto? 

Un *objeto* es una *entidad* que contiene una *coleccion de propiedades*. 

Una propiedad es una asociacion de clave-valor.

Las propiedades son similares a las variables comunes de JavaScript, la diferencia es que las propiedades son variables que están unidas a un determinado objeto.

El valor de una propiedad puede ser una función y en ese casi a la propiedad se le llama *método*.

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/clase9-Tema1-objeto.png?raw=true)

----------------------------------------------------------------

El concepto de objeto es similar al de la vida real...

Ejemplo: un *auto*.Básicamente es un objeto que tiene un monton de propiedades como: color, pero, marca, modelo, velocidad maxima, kilometraje, etc.

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/clase9-Tema1-objeto-concepto.png?raw=true)

----------------------------------------------------------------
Acceder a una propiedad de un objeto

Dado el objeto llamado persona1:

![](https://github.com/lorecarreno/curso-preparacion-hack-academy/blob/main/images/clase9-Tema1-objeto-acceder-propiedad.png?raw=true)

Se accede a sus propiedades de esta forma:

> ``persona.apellido; //Devuelve "Rodriguez"`` <br>
> ``peronsa.edad; // Devuelve 36.`` <br>

----------------------------------------------------------------
**Entonces los arrays son objetos? (1/2)**

Si. Se podría decir que los arrays son un caso particular de objetos en los que las claves de las propiedades son números naturales (que empiezan en cero).

Ejemplo:

var usuarios = {
    0: "María",
    1: "Juan",
    2: "Martin",
    4: "Lucia"
};

usuarios[2]; // Retorna el string "Juan".

----------------------------------------------------------------
**Entonces los arrays son objetos? (2/2)**

Visto de otra forma, los pobjetos son arrays donde en lugar de estar obligados a usar números naturales como índices podemos crear nuestros propios índices.

Entonces, también es posible acceder a las propiedades de un objeto de esta forma:

> ``persona["apellido"];`` // Devuelve "Rodriguez". Esta notación se llama "Bracket Notation".

Equivalente a:

> ``persona.apellido;`` // Devuelve "Rodriguez". Esta notación se llama "Dot Notation".

Nota: A veces, a los objetos en JavaScript se les llama "Arrays Asociativos" (o incluso "Hash Maps").


----------------------------------------------------------------
**Asignar una propiedad a un objeto**

Visto de otra forma, los objetos son arrays donde en lugar de estar obligados a usar números naturales como índices podemos crear nuestros propiso índices.

Entonces, también es posible acceder a las propiedades de un objeto de esta forma:

> ``persona["apellido"] = "Pérez";`` <br>
> ``persona.apellido = "Pérez";`` 




