# Introducción al Desarrollo Web.

- Preguntas:
1. ¿Por qué es importante utilizar elementos semánticos en nuestro HTML?
>_Porque de esta manera nuestra web puede verse beneficiada para influir en la clasificacion de busqueda, tambien de esta forma se le da un sentido y significado a la pagina, de esta manera obtener una apariencia correcta._
2. ¿Cuántos niveles de encabezado existen en HTML?
>_Hay 6 niveles de encabezado: h1, h2, h3, h4, h5, h6. (Siendo h1 el titulo,h2 el subtitulo y el h3 el subtitulo del subtitulo, y asi sucesivamente)._
3. ¿Cuáles son algunos de los usos para los elementos <sup> y <sub>?
>_El elemento <sup> se utiliza para hacer superindices como pueden ser algunas formulas o para algunas fechas._ 
- 25<sup>th</sup> 
>_El elemento <sub> se utiliza para hacer subindices como pueden ser algunas formulas quimicas._ 
- C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub>.
4. Al utilizar el elemento <abbr>, qué atributo se debe añadir para proporcionar una ampliación del término?
>_Se debe utilizar el atributo <Title> para colocar una ampliacion de la abrebiatura._

## Aprendiendo CSS:

1. ¿De qué formas podemos añadir CSS a nuestro HTML?
>_Se puede añadir mediante una hoja externa y copiando el link dentro del HTML, otra opcion es mediante una hoja de estilos interna y por ultimo se puede añadir estilos en linea._
2. ¿Por qué deberíamos evitar utilizar estilos inline?
>_Puede resultar confuso a la hora de modificar un codigo ya que probablemente tendriamos que actualizarlo varias veces, esto tambien dificulta un poco la lectura del codigo, es mejor mantener siempre hojas separadas._
- Revisa el código a continuación y responde a las siguientes preguntas:
   h2 {
     color: black;
     padding: 5px;
   }

3. ¿Qué representa el selector?
>_En este caso el selector representa a un subtitulo (h2), las  propiedades se aplicarian a todos los h2 en el documento._
4. ¿Qué componentes son declaraciones CSS?
>_La declaracion del codigo de CSS es la que define una propiedad y un valor para esa propiedad, es este caso esas declaraciones están contenidas dentro de los corchetes { }._
5. ¿Qué componentes se consideran propiedades?
>Estos se consideran propiedades:
- color: black;
- padding: 5px;

## Aprende JS:

1. ¿Qué tipo de dato es una secuencia de texto entre comillas simples?
>_El tipo de dato seria string, ya que seria texto._
2. Enumera 4 tipos de operadores en JavaScript.
>_Los 4 tipos de operadores serian:
- '+' (suma)
- '-' (resta)
- '*' (multiplicación)
- '/' (división)

3. Describe un problema práctico que puedes resolver con una función.
>_Ejemplo:

>// Definición de la función para verificar si un número es positivo
>const esPositivo = num => num > 0;

>// Uso de la función:
>console.log(esPositivo(5));  // true
>console.log(esPositivo(-3)); // false
>onsole.log(esPositivo(0));  // false

4. Si una declaración if comprueba una CONDICION y si resulta TRUE, entonces el código se ejecutará.
5. ¿Cuál es el uso del else if?
>_El else if se usa para evaluar una condición adicional si la condición anterior en un bloque if no se cumple, permitiendo manejar múltiples casos de manera estructurada y eficiente._
6. Enumera 3 tipos de operadores de comparación.
>_Tipos de operadores de comparacion:
- Operador de igualdad (==)
- Operador de estricta igualdad (===)
- Operador de menor que (<)
7. ¿Cuál es la diferencia entre los operadores lógicos && y ||?
>_El operador lógico && (AND) devuelve true si ambas expresiones son verdaderas, por otro lado, || (OR) devuelve true si al menos una de las expresiones es verdadera.
- NOTA: Si ninguna expresión es verdadera, && devuelve false, mientras que || devuelve false si ambas son falsas.