# Imágenes, Color, Texto y más trabajo con Funciones.

- Preguntas:
## Medios en HTML.
1. ¿Cuál es un caso práctico del atributo alt en una página web?
>_Para describir una imagen en el caso de que esta no pueda ser mostrada o tarde en cargarse por temas de internet lento._
2. ¿Cómo puedes mejorar la accesibilidad de las imágenes en un documento HTML?
>_Se puede mejorar usando el atributo alt o tambien el elemento figcaption dentro de un figure, preferible usar imagenes sin derechos de autor._
3. Da un ejemplo en el que el elemento figure sería útil en un documento HTML.
>_Por ejemplo con una fotografia de un atardecer sobre el mar. Para mejorar la accesibilidad y la estructura semántica de tu documento HTML, puedes agrupar esta imagen junto con una descripción utilizando el elemento <figure>. Dentro de este contenedor <figure>, colocarías la imagen y debajo de ella añadirías un pie de foto utilizando <figcaption>._
4. Describe la diferencia entre una imágen gif y una imágen svg, imagina que se lo estás explicando a una persona mayor de tu comunidad.
>_Ejemplo._
- _GIF: Es un tipo de imagen que puede mostrar movimiento, como una pequeña película. Se usa para imágenes simples y animadas, como los dibujos animados que ves en internet. No se ve bien si la agrandas mucho._

- _SVG: Es un tipo de imagen que se dibuja con líneas y formas, como un dibujo en papel. Puedes agrandarla o achicarla todo lo que quieras y siempre se verá clara. Es ideal para logotipos y gráficos en la web._
5. ¿Qué tipo de imagen usarías para mostrar una captura de pantalla en tu página web y por qué?
>_Usaria el tipo de imagen de PNG. Porque ofrece una alta calidad de imagen y preserva los detalles importantes sin pérdida de información._

## Aprende CSS
1. Describe la diferencia entre un color de primer plano y un color de fondo de un elemento HTML, imagina que estás hablando con una personas sin conocimientos técnicos.
>_Ejemplo._
- _Color de primer plano: Es el color que se aplica al contenido dentro de un elemento, como el texto. Imagina que escribes una carta con un bolígrafo rojo; el color del texto sería el color de primer plano._

- _color de fondo: Es el color que se aplica detrás del contenido, cubriendo el área del elemento. Usando el ejemplo de la carta, si el papel de la carta es azul, ese sería el color de fondo._

2. Tu amigo te pide que le des un retoque a su blog. ¿Cómo utilizarías color para darle carácter a su blog?
>_Podria buscar una paleta de colores adecuada para el blog, de acuerdo a esto, podria implementarla en primer plano y en color de fondo, podria buscar unos buenos estilos para el texto, mejoraria la jerarquia del texto y tambien se destacaria los elementos importantes._
3. ¿Qué debes tener en cuenta al escoger tipos de letra para un documento HTML?
>_Debo de tener en cuenta la legibilidad, la compatibilidad, los tamaños y las jerarquias, etc._
4. ¿Cuál es la relación entre font-size, font-weight, y font-style con los elementos de texto en HTML?
>_Pues el font-size define el tamaño del texto._
>_El font-weigth ajusta el grosor del texto._
>_font-style define el estilo del texto sea cursiva, normal o italica_
5. Describe dos formas de añadir espaciado alrededor de los caracteres mostrados en un elemento h1.
>_Ejemplo.
-h1 {
    letter-spacing: 2px; /* Aumenta el espaciado entre caracteres */
}
- h1 {
    padding: 10px; /* Añade 10 píxeles de espacio alrededor del texto */
}