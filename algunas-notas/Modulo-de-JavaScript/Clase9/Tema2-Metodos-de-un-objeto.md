
<h1> Métodos de un objeto </h1>

----------------------------------------------------------------
**Métodos de un objeto**

Cuando una propiedad recibe como valor una función, se le llama método.

> ``var persona = {`` <br>
> ``    nombre: "María",`` <br>
> ``    apellido: "Rodriguez",`` <br>
> ``    edad: 36,`` <br>
> ``    email: "maria.rodriguez.com",`` <br>
> ``    nacionalidad: ["Uruguay", "España"],`` <br>
> ``    nombreCompleto: function () {`` <br>
> ``        return this.nombre + " " + this.apellido;`` <br>
> ``    },`` <br>
> ``};``

persona.nombreCompleto(); // Retorna "María Rodríguez"

----------------------------------------------------------------
**This**

----------------------------------------------------------------

Usar this para referencias a objetos

La palabra clave *this* se refiere al objeto actual en el que se está escribiendo el código, por lo que en este caso *this* es equivalente a la persona.

> ``var persona = {`` <br>
> ``nombre: "María",`` <br>
> ``apellido: "Rodriguez",`` <br>
> ``edad: 36,`` <br>
> ``email: "maria.rodriguez.com",`` <br>
> ``nacionalidad: ["Uruguay", "España"],`` <br>
> ``nombreCompleto: function () {`` <br>
> ``return this.nombre + " " + this.apellido;`` <br>
> ``},`` <br>
> ``};`` 

*this* siempre asegurará que se usen los *valores correctos* cuando cambie el contexto (por ejemplo, dos diferentes instancias de objetos *persona*). Pueden tener diferentes nombres, pero querrás usar su propio nombre y apellido, al decir su nombreCompleto.


