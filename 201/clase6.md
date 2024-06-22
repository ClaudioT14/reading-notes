# Modelos de Dominio, Introducción al DOM y Notaciones de Objetos Literales.

- Preguntas:
## Objetos JavaScript.
1. ¿Cómo le describirías un objeto a un amigo sin conocimiento técnico con el que creciste?
>_Un objeto es como una caja que guarda diferentes cosas (como fotos, juguetes, etc.) organizadas con etiquetas para encontrarlas fácilmente. Cada etiqueta tiene un nombre y un valor. Así, puedes abrir la caja y rápidamente encontrar lo que buscas usando las etiquetas._
2. ¿Cuáles son algunas de las ventajas de crear objetos literales?
>_Algunas de las ventajas es que todo esta mejor estructurado y ordenado, tambien que puedes usarlo para distintas ideas que se te ocurran_
3. ¿En qué se diferencian los objetos de los arrays?
>_En lo que es estructura los objetos constan de clave-valor, donde las claves son unicas y los valores son especificaciones de cada clave, en los arrays, los valores estan puestos de forma listada con idices para cada uno._
4. Da un ejemplo acerca de los momentos en los que necesitarías utilizar bracket notation para acceder a la propiedad de un objeto en vez de dot notation.
>_Ejemplo:_
>
-  const persona = {
  "primer nombre": "Juan"
  };
console.log(persona["primer nombre"]); // "Juan"
5. Evalúa el siguiente código. ¿A qué se refiere el término this y cuál es la ventaja de utilizarlo?
>Codigo:
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

>_El this se refiere a ese mismo objeto en el que se encuentra, hace referencia al name y al age. Una de las ventajas es que no necesitas duplicar el mismo codigo y todo se mantiene de forma clara._

## Aprendiendo del DOM.
1. ¿Qué es el DOM?
>_el DOM actúa como una interfaz que JavaScript utiliza para manipular y actualizar la estructura y contenido de una página web de manera dinamica(Modifica la visualizacion del HTML si editar el codigo index.html)._
2. Describe brevemente la relación entre el DOM y JavaScript.
>_El DOM es ina interfaz que permite acceder a los programas y modificar documentos HTML y XML estructuradamente.Representa documentos como objetos que pueden ser cambiados mediante propiedades y métodos, conectando paginas web con scripts o lenguajes de programacion.