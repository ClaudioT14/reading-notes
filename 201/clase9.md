# Formularios y Eventos.

- Preguntas:
## Formularios en HTML.
1. ¿Por qué los formularios son tan importantes en el desarrollo web?
>_Son impoetantes porque de esa forma podemos recopilar datos sobre nuestros clientes, nos puede ayudar en temas de seguridad, accecibilidad y una iteraccion con el usuario._
2. Al diseñar un formulario, ¿cuáles son algunas de las cosas más importantes a tener en cuenta sobre la experiencia de usuario?
>_Algunas cosas importantes es que sea simple, claro e intuitivo, se pueda adaptar a distintos dispositivos. Se pueden implementar indicadores sobre el progreso del formulario._
3. Enumera 5 elementos de los formularios y explica su importancia.
>_Algunos elementos son: form, label, input, textarea y button._
>_form: Con este elemento se empieza la estructura de un formularion (es un contenedor), pero solo especificamente para colocar formularios._
>_label: Proporciona una etiqueta descriptiva para un campo de entrada, mejorando la accesibilidad._
>_input: Crea varios tipos de campos de entrada como texto, contraseñas, casillas de verificación, radios, etc._
>_textarea: Proporciona un campo de entrada de texto multilinea._
>_button: Crea un botón que puede enviar el formulario o ejecutar una acción específica._

## Aprende JS.
1. ¿Cómo describirías los event a un amigo sin conocimiento técnico?
>_Los eventos describen las acciones que uno vaya a realizar dentro de una web, es decir, si por ejemplo das click en un boton o el usuario presiona algo en el teclado, esto puede tener distintos finales, se puede mostrar un mensaje con lo sucedido o tal vez cambiar algo en la pantalla._
2. Al utilizar el método addEventListener(), ¿cuáles son los 2 arguments que debes proporcionar?
>_La cadena primero para ver que es lo que vamos a detectar de evento, ya sea un click, mouseover o tal vez un keydown. Y segundo se coloca la funcion que se va a llamar para que esta se ejecute._
3. Describe el objeto event. ¿Por qué el target dentro del objeto event es útil?
>_El objeto event representa cualquier accion dentro de la pagina, el target dentro del objeto event es util porque puede indicar el elemento espacifico en el que ocurrio el evento, permitiendo que reacione a la interaccion de usuario._
4. ¿Cuál es la diferencia entre event bubbling y event capturing?
>_event bubbling, el evento empieza del elemento especifico y va propagandoce hacia los elementos padres de el.(Es como una burbuja cuando sube)._
>_event capturing, se propaga desde el document hacia abajo hasta el elemento más específico en orden descendente, capturando el evento antes de llegar al objetivo._