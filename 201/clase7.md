# Tablas en HTML y Funciones Constructoras en JS.

- Preguntas:
1. Explica por qué necesitamos los modelos de dominio.
>_Se necesita un modelo de dominio para poder validar y verificar problemas especificos y la estructura de este._
2. ¿Por qué no se debe utilizar tablas para los layout de página?
>_Porque no puede ser accecible para otros dispositivos y tal vez dificulte el rendimiento, tambien es posible que para los motores de busqueda sea dificil de interpretar la informacion de una tabla._
3. Enumera y describe 3 diferentes elementos semánticos HTML utilizados en un <table>.
>_<td/> 'table data', esta se conforma por una primera celda._
>_<tr/> 'table row' esto hara que las celdas formen una fila._
>_<th/> 'table header' este funciona igual que los td pero, th formula un encabezado, no una celda normal._
4. ¿Qué es un constructor y cuáles son las ventajas de utilizarlo?
>_Un constructor es un método especial utilizado para crear un objeto. Además, se encarga de inicializar dicho objeto a partir de una clase.
5. ¿Cómo es que el término this se diferencia cuando se utiliza en un objeto literal y cuando se utiliza en un constructor? 
>_En un objeto literal se diferencia por hacer referencia al propio objeto en el que esta siendo llamado, se usa para acceder a propiedades y metodos del mismo objeto._
>_En un constructor se diferencia por referirse a la nueva instancia del objeto que está siendo creada. Se utiliza para inicializar las propiedades del nuevo objeto._
6. Explica los prototipos y las herencias por medio de una analogía sobre tu experiencia laboral previa.
NOTA: Esta es una pregunta común en las entrevistas para desarrolladores front end.
>_Los prototipos pueden ser parte de un objeto los cuales pueden ser heredados por metodos y propiedades. Esto se puede asimilar a un empleado basico con ciertas caracteristicas las cuales tiene en comum con otros empleadores por ejemplo._
>_En esta analogía, el Empleado básico es el prototipo de todos los empleados, el objeto GerenteProyecto heredan de Empleado, lo que significa que adquieren las habilidades básicas (métodos) definidas en el prototipo de Empleado. Además, cada uno añade sus propias habilidades específicas._