# Listas, Box Model y Bucles.

- Preguntas:
## Aprende HTML.
1. ¿Cuándo se puede utilizar una lista no ordenada en tu documento HTML?
>_Cuando necesitas elaborar una lista pero no requieres un orden especifico, se puede usar como para menus de navegacion o por ejemplo listas de tareas, es preciso para adjuntar elementos  claros sin importar su secuencia._
2. ¿Cómo cambias el estilo bullet de la lista de elementos no ordenados?
>_Se cambia a traves de css con la propiedad ;list-style-type: none', y dejara de tener estilo bullet._
3. ¿Cuándo debes usar una lista ordenada o lista no ordenada en tu documento HTML?
>_Una lista ordenada se usa cuando es necesario especificar una secuencia importante o tal vez un top o ranking, en cambio, una lista no ordenada se usa cuando la secuencia no es importante, tambien se usa para poner menus de navegacion o algunas listas de tareas; la eleccion depende de la importancia de los contenidos._
4. Describe dos formas en las que puedes cambiar los números en los elementos de la lista proporcionados por una lista ordenada.
>_Se puede utilizar un atributo dentro del (<ol>), el atributo seria 'type'._
< ol type="i">
  < li>Elemento 1</li>
  < li>Elemento 2</li>
  < li>Elemento 3</li>
< /ol>

>_Otra forma seria modificarlo mediante la hoja de css._
< style>
  /* Números romanos en mayúsculas */
  ol.roman {
    list-style-type: upper-roman;
  }
  /* Letras en minúsculas */
  ol.alpha {
    list-style-type: lower-alpha;
  }
< /style>


## Aprende CSS.
1. Describe las propiedades de margin y padding en CSS como si fueran los personajes de una historia. ¿Cuál es su rol en la historia: “El Box Model”?

>_Érase una vez, un reino con el nombre de Diseño Web, en este reino habia un modelo de trabajo el cual era "El Modelo de Caja". Aqui pues cada elemento de todo el reino era una caja mágica con capas de propiedades que le daban un comportamiento especifico y una apariencia con estilos unicos. De eso se encargaban Margin y Padding, dos personajes vitales en la historia._

_Pues Margin se encargaba de que todas las cajas esten en su espacio, sin chocar con otras, el era como el aire que rodeaba las cajas, el que ponia los limites entre ellas para que de esta manera se vean todas ordenadas.Características: Podía cambiar su tamaño en todas las direcciones (top, right, bottom, left) dependiendo de las necesidades del diseño._

_Y Padding era el principal administrador de las cajas el que se aseguraba que dentro de estas cajas no falte nada y este todo en su sitio, el que verificaba que dentro de cada caja haya un espacio libre para que no haya nada ajustado contra las paredes.Características: Al igual que Margin, Padding podía ajustar su tamaño en todas las direcciones (top, right, bottom, left) para ofrecer el espacio necesario._

_A pesar de que Margin y Padding tenían roles diferentes, trabajaban siempre en conjunto para elegir las distintas apariencias y los espaciados de todas las cajas de el reino del Diseño Web. Ellos dos se aseguraban que el reino del Diseño Web fuera un lugar organizado y visualmente atractivo, donde cada una de esas cajas podían coexistir en armonía y conformes. Y así, la historia del Box Model continuó, con Margin y Padding desempeñando sus papeles esenciales para mantener la paz y la estética en el reino._

2. Enumera y describe las cuatro partes de un box del elementos HTML según el box model.
>_Las cuatro partes del Box Model son:_
1. _Content: Área que contiene el contenido real del elemento._
2. _Padding: Espacio entre el contenido y el borde, que da espacio interno al contenido._
3. _Border: Línea que rodea el padding y el contenido, definiendo el límite del elemento._
4. _Margin: Espacio exterior alrededor del borde, separando el elemento de otros elementos._


## Aprende JS.
1. ¿Qué tipos de datos puedes almacenar en un Array?
>_En un Array se pueden almacenar distintos tipos de datos, de esta forma se puede almacenar los datos que uno desee ya que no hay restricciones sobre algun tipo de dato._

2. ¿El array people es un array de JavaScript válido? De ser así, ¿cómo puedo acceder a los valores almacenados? Y si no, ¿por qué?

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

 >_Si es valido el Array, Se puede acceder a los valores almacenados utilizando las llaves. [] Ejemplo:_

 // Acceder al primer elemento del primer sub-Array (['pete', 32, 'librarian', null])
const primerPersona = people[0];

// Acceder a la edad de la segunda persona (40)
const edadSegundaPersona = people[1][1];

// Acceder a las aficiones de la segunda persona (['fishing', 'hiking', 'rock_climbing'])
const aficionesSegundaPersona = people[1][3].split(':');

// Acceder al nombre de la tercera persona ('bill')
const nombreTerceraPersona = people[2][0];

3. Enumera cinco opreadores abreviados de asignación en javascript y describe lo que hacen.
>_Asignacion: x = y._
>_Adicion: x += y._
>_Resta: x -= y._
>_Multiplicacion: x *= y._
>_Division: x /= y._

4. Lee el código a continuación, evalúa la últimaexpresión y explica cuál sería el resultado y por qué.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evalúa esto
 (a + c) + b;

 >_La expresión (a + c) intenta hacer una suma (a, que es 10) con un booleano (c, que es false). El booleano false se convierte en un 0 en la operación de suma. Entonces, (a + c) es igual a 10. Luego, se intenta sumar el resultado (10) con la cadena 'dog', lo que resulta en la concatenación de '10' y 'dog', produciendo '10dog'._
5. Describe un ejemplo cotidiano de por qué una declaración condicional se debería usar en un programa en JavaScript.
>_Se podria usar para enviar un mrecordatorio solo si una fecha y hora de una tarea ya caduco, de lo contrario no se mandara ninguna notificacion, asi se aseguran que las notificaciones sea importantes y oportunas._
6. Da un ejempo de por qué un Bucle es últil en JavaScript.
>_Podria ser util para iterar sobre todos los elementos de un listado de tareas por cumplir y realizar una acción en cada una de estas, como eliminarlas, como culminadas o pendientes. Esto te ayuda a ahorrar el tiempo y esfuerzo al automatizar la tarea repetitiva de manejar cada elemento de la lista por separado._
