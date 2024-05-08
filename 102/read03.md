# Versionamiento local y remoto.
1. ¿Qué es el control de versiones?
> _Es una herramienta que permite revisar un archivo y sus distintas versiones o varios archivos con cambios registrados, esta herramienta ayuda a seguir las modificaciones de un archivo, tambien regresarlos a una version anterior y corregir errores en archivos._
Hay 3 tipos:
> Control de versiones local: _Este implica que los cambios y los archivos esten en su disco duro._
> Control de versiones centralizado: _Aqui en el CVCS, los cambios y versiones estan centralizados en un servidor, de esta manera es mas controlable y permite ver las actividades de un equipo de trabajo._
> Control de versiones distribuidas: _Un DVCS soluciona la vulnerabilidad del CVS al permitir repositorios reflejados, evitando pérdidas de trabajo en caso de fallos del servidor o corrupción de datos en un disco duro. Esto facilita la colaboración entre equipos al permitir múltiples flujos de trabajo simultáneos._

2. ¿Qué es “clone” en Git?
> _Es un comando que te permite clonar o crear copia de un repositorio existente dentro de Git en un servidor particular._
> **Ejemplo** -> ($ git clone https://github.com/test)

3. ¿Cuál es el comando para rastrear y preparar archivos?
> _Para rastrear los archivos se colocan los siguientes comandos:_
> Rastreo: git add filename
> Preparar: git status

4. ¿Cuál es el comando para tomar una instantánea de los archivos modificados?
> _El comando para tomar instantanea de archivos modificados es el siguiente:_
> $ git commit -a

5. ¿Cuál es el comando para enviar los archivos modificados a Github?
> _El comando para enviar archivos modificados a Github es el siguiente:_
> git push [nombre remoto][nombre-rama]
