# Configuración de Herramientas para Desarrolladores.

- Preguntas:
1. Crea un poema corto describiendo cómo HTTP envía datos entre computadoras.
2. Describe como los archivos HTML, CSS y JS son “analizados” en el navegador.
> _El navegador descompone HTML, CSS y JavaScript, luego los junta todos para crear el diseño y hacer que la página se vea adecuada. Ahi es donde se construye el DOM, CSSOM, luego combian estos dos para calcular el layout y pintar la página (JavaScript)._
3. ¿Cómo puedes encontrar imágenes para agregar a una página web?
> _Puedes buscar algo adecuado a travez de Google imagenes, accede a la imagen de forma ampliada y luego guarda la imagen en la carpeta que desees y copia tambien la direccion web para su proximo uso. Ten cuidado a la hora de descargaar la imagen de Google ya que la mayoria de estas tienen derechos de autor, puedes usar un filtro o buscar en pagina con imagenes libres de derechos._
4. ¿Cómo creas una String en comparación con un Number en Javascript?
>_Para crear un string se usa lo siguiente: let miVariable = 'Bob'; y para crear un Number se usa: let miVariable = 10;._
5. ¿Qué es una Variable y por qué son importantes en JavaScript?
>_Las Variables son contenedores en los que puedes almacenar valores. Primero debes declarar la variable con la palabra let, despues el nombre que le quieras dar._ 

- Introducción a HTML.

1. ¿Qué es un atributo en HTML?
>_Es informacion adicional que no aparece en pagina renderizada y pertenece a un elemento, estos atributos pueden ser por ejemplo src, alt, width, etc, existen variedad de atributos a colocar._
2. Describe la anatomía de un elemento en HTML.
>_La anatomia de un HTML se conforma por etiquetas de apertura, el contenido dentro de la etiqueta, una etiqueta de cierre y por ultimo se le denomina elemento a la combinacion de las etiquetas con el contenido dentro de estas.
3. ¿Cuál es la diferencia entre las etiquetas <article> y <section>?
>_Use <article> para contenido independiente que podría ser redistribuido de manera autónoma._
>_Use <section> para agrupar contenido relacionado dentro de una página, proporcionando estructura y organización._
4. Qué elementos se incluyen en una página web “típica”?
>_Se incluye el header, los H1 o H2, <p>(Parrafos) y talvez algunos <a>(Anchor-Ancla)_
5. ¿Cómo influyen los metadatos en el Posicionamiento en buscadores (SEO)?
>_Los metadatos influyen en el SEO al ayudar a los motores de busqueda a entender y clasificar el contenido de una pagina web. Elementos como el titulo, la descripción meta mejoran el CTR y su vcisibilidads. Además, los datos estructurados y las etiquetas alt de imágenes también contribuyen a una mejor indexación y accesibilidad._
6. ¿Cómo se utliza la etiqueta <meta> en HTML cuando se quiere especificar metadatos?
>_Normalmente estos se utilizan en la parte del <head> de un doc hmtl._
>_Ejemplo:_
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Descripción de la página">
    <meta name="keywords" content="palabra1, palabra2">
    <meta name="author" content="Nombre del autor">
</head>


- Miscelánea.

1. ¿Cuál es el primer paso para diseñar una página web?
>_El primer paso para poder lograr tener una pagina web es preguntarnos 
- ¿Qué es exactamente lo que quiero lograr?
- ¿Cómo un sitio web me ayudará a alcanzar mis metas?
- ¿Qué es necesario hacer, y en qué orden, para alcanzar mis metas?
>_NOTA: La mayoria de proyectos fallan, no por falta de conocimiento técnico sino por falta de objetivos y visión.
2. ¿Cuál es la pregunta más importante que se debe responder al diseñar una página web?
>_La pregunta mas importante a reponder es: ¿Qué es exactamente lo que quiero lograr?, esta pregunta es el inicio y la motivacion que debes tener para poder realizar lo demas.

- Semántica.

1. ¿Por qué se debe utilizar un elemento h1> en vez de un span para mostrar un título de primer nivel?
>_Se debe de usar h1 por que de esa manera se obtiene un valor semantico y siempre se usa para encabezados, span es para que simplemente parezca un encabezado, y no tendra valor semantico, por lo que no tendra ningun beneficio adicional._
2. ¿Cuáles son los beneficios de utilizar etiquetas semánticas en nuestro HTML?
>_Estos son algunos beneficios:_
- _Los motores de búsqueda considerarán su contenido como palabras clave importantes para influir en las clasificaciones de búsqueda de la página (ver SEO)._
- _Los lectores de pantalla pueden usarlo como señal para ayudar a los usuarios con discapacidad visual a navegar por una página._
- _Sugiere al desarrollador el tipo de datos que se rellenarán._
- _La nomenclatura semántica refleja la denominación de elementos/componentes personalizados adecuados._

- ¿Qué es JavaScript?

1. Describe 2 cosas que requieran de JavaScript en el navegador.
>_Mostrar un mensaje emergente meidante un prompt sería un ejemplo de interactividad básica que requiere JavaScript en un navegador, o talvez un reloj que simplemente te muestre la hora._
2. ¿Cómo se puede añadir JavaScript a un documento en HTML?
>_Primero, ve a tu sitio de pruebas y crea una carpeta llamada scripts. Luego, dentro de la nueva carpeta de scripts, crea un nuevo archivo llamado main.js y guárdalo._
_A continuación, abre tu archivo index.html e introduce el siguiente código en una nueva línea, justo antes de la etiqueta de cierre </body>:_
_Ejemplo: <script src="scripts/main.js"></script>_
