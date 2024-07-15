# Audio y Video en HTML; Revisión de Modelos de Dominio.

- Preguntas:
1. Explica cómo la capacidad de utilizar video y audio en la web ha ido evolucionando desde el comienzo de los 2000.
>_Desde el 2000 se empezo a implementar mas los videos en Html gracias a flash y silverlight, estos tenian mas peso que texto y que imagenes, poco a poco se fue implementando en distintas webs._
2. Describe el uso de los atributos src y controls en el elemento <video>.
>_El atributo src, funciona para poder incrustar una url de un video en el codigo html, y controls sirven para poder mostrar los controles de mando para ese video._
3. ¿Por qué es importante tener contenido de respaldo en el elemento <video>?
>_Nos ayuda a tener mejor accesibilidad y tambien y compatibilidad para todos los usuarios y la experiencia sea correcta y mostrar un mensaje si el video no se reproduce._
4. Escribe una historia corta en donde <audio> y <video> son personajes.
>_En un pequeño pueblo digital, vivían Audio y Video, dos amigos inseparables. Audio, con su voz melodiosa, narraba cuentos que hechizaban a todos. Video, con sus imágenes vibrantes, daba vida a esas historias, haciendo que todo pareciera real. Un día, una tormenta de bugs atacó el pueblo, y Audio y Video trabajaron juntos para restaurar la armonía, demostrando que cuando se combinan, crean experiencias inolvidables. Desde entonces, fueron considerados los héroes del entretenimiento en el pueblo digital._
5. ¿En qué se diferencia el layout Grid del Flex?
>_Grid Layout: Grid es bidimensional, manejando filas y columnas para diseños completos de página, con control detallado de posición y áreas nombradas._
>_Flex Layout: Flex es unidimensional, ideal para alinear elementos en una fila o columna, distribuyendo espacio entre ellos sin áreas nombradas._
6. Grid container, grid item, y grid line son algunos de los términos importantes que se deben entender al utilizar Grid. Por favor describe estos términos en unas pocas frases.
>_Grid Container: Es el contenedor que define un contexto de cuadrícula, donde los elementos hijos se distribuyen en filas y columnas. Se crea aplicando la propiedad display: grid o display: inline-grid a un elemento._
>_Grid Item: Son los elementos hijos directos de un grid container. Estos elementos se colocan dentro de las filas y columnas definidas por la cuadrícula._
>_Grid Line: Son las líneas horizontales y verticales que dividen la cuadrícula en celdas. Se utilizan para posicionar y dimensionar los grid items dentro del grid container._

## Imágenes Responsivas:
1. Además de hacer que un sitio se vea atractivo visualmente en diferentes tamaños de pantalla, ¿por qué los desarrolladores deberían hacer imágenes responsivas?
>_Porque de esta manera mejora el rendimiento de un sitio web, mejora la optimizacion para el SEO, cumple con accesibilidad y se le puede dar un mejor mantenimiento_
2. Define los siguientes atributos de <img>: srcset y sizes. Escribe un ejemplo de cómo se usan.
>_srcset:_
- _images/image-400.jpg 400w: Imagen de 400 píxeles de ancho._
- _images/image-800.jpg 800w: Imagen de 800 píxeles de ancho._
>_sizes:
- _(max-width: 600px) 100vw: Si la ventana gráfica es de 600 píxeles de ancho o menos, la imagen debe ocupar el 100% del ancho de la ventana (100vw)._
- _(max-width: 1200px) 50vw: Si la ventana gráfica es de 1200 píxeles de ancho o menos, la imagen debe ocupar el 50% del ancho de la ventana (50vw)._
3. ¿Cómo es que srcset es más útil para las imágenes responsivas que CSS o JavaScript?
>_srcset permite al navegador elegir y cargar la imagen más adecuada según la resolución y tamaño de la pantalla, a diferencia de CSS o JavaScript, srcset proporciona una solución eficiente y directa para imágenes responsivas, esto mejora la experiencia del usuario y la compatibilidad SEO._
