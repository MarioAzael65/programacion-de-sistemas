# programacion-de-sistemas
Aquí están todas mis prácticas echas en esta materia

## Ensamblador
Un ensamblador traduce el código escrito en lenguaje ensamblador directamente a código binario, cuyo código se puede crear manualmente o por máquina. Por ejemplo, algunos compiladores primero convierten el código del programa en código ensamblador y luego llaman a un ensamblador. Esto, a su vez, funciona como un compilador en sí mismo y, como paso final, crea el código máquina. <br>

## Ligadores

### ¿Que es un ligador?

Un ligador es un programa de sistema que combina dos o mas programas objeto separados y permite que se hagan referencias unos a otros, o sea, que cada uno de estos programas pueda hacer referencia a código ó variables de los otros programas con los que está enlazado. En muchos programas el cargador hace la labor del programa de enlace, porque existe solo un «linking loader» y no existe programa de enlace independiente. Es importante señalar que no se necesita un programa de enlace ni un cargador separado para cada traductor en el sistema, ya que estos programas trabajan con el programa objeto, sin importar el lenguaje fuente. Por otro lado es importante que cada compilador o ensamblador produzca el programa objeto usando el mismo formato. Cada programa objeto es un archivo de récord.<br>

### ¿Que es una biblioteca?

una biblioteca es un conjunto de subprogramas utilizados para desarrollar software. Las bibliotecas contienen código y datos, que proporcionan servicios a programas independientes, es decir, pasan a formar parte de estos. Esto permite que el código y los datos se compartan y puedan modificarse de forma modular. Algunos programas ejecutables pueden ser a la vez programas independientes y bibliotecas, pero la mayoría de estas no son ejecutables.<br>

### ¿Que es una biblioteca estatica?

Una biblioteca estática es un conjunto de archivos objeto creado, comúnmente, con el programa ar. La diferencia principal con una biblioteca dinámica es que las bibliotecas estáticas son enlazadas al compilar, lo que hace que el tamaño del ejecutable aumente. Es decir, no aparecen como archivos independientes.<br>
Por último, destacar que las bibliotecas estáticas son colecciones de ficheros-objeto agrupadas en un único archivo, cuya extensión suele ser .lib (Windows) o .a (Mac). Este archivo suele ir acompañado de un archivo de cabecera (extensión .h) el cual va a contener las definiciones de todas las funciones utilizadas en la biblioteca en cuestión. Una vez en el enlazador, el linker incluye en el ejecutable los módulos correspondientes a las funciones y bibliotecas utilizadas por el programa. Así, las funciones de una biblioteca son enlazadas de la misma manera en que lo haría cualquier otra función declarada dentro de los archivo que conforman el programa.<br>

### ¿Que es una biblioteca compartida?

Las Bibliotecas compartidas son ficheros que contienen colecciones de  fragmentos de código, que nos permite el poder utilizarlos en el nuestro código o/y por los programas que tenemos instalados en nuestra máquina, sin tener que volver a programar ciertas tareas rutinarias (p.e. crear ventanas, botones, acceso a dispositivos, ... ).<br>

Además de ahorrarnos tiempo a la hora de desarrollar aplicaciones, y posibles errores, estas bibliotecas al ser compartidas se instalan en nuestra máquina y como su nombre indica son o pueden ser compartidas por varios programas, consiguiendo así:<br>
<ul>
  <li>Ahorrar espacio de almacenamiento.</li>
  <li>Se cargan una sola vez en memoria, independientemente de las aplicaciones que las requieran</li>
 </ul>
 <br>

#### Actividad de biblioteca estatica y compartida

En la practica la maestra nos compartio un PDF por Teams donde venian las instrcuciones de lo que deberiamos hacer, para ver como funcionanban estas bibliotecas, y que pasaba si solo se compartia el archivo .exe con otro compañero.<br>

con la <strong>biblioteca estatica</strong> esto fue lo que ocurrio al ejecutar el .exe.<br>

![biblioteca estatica](https://user-images.githubusercontent.com/113700163/190680485-773bac7a-17c0-400c-8eb6-77a1e524dcd1.png)<br>

con la <strong>biblioteca compartida</strong> comparti el archivo con mi compañero Juan y el compartio su archivo conmigo y esto fue lo que me mostro al ejecutar el archivo.<br>

![biblioteca dinamica juan](https://user-images.githubusercontent.com/113700163/190681078-bd732e24-0567-4360-a5a6-a32e61089762.png)<br>

esto es lo que aparecio al ejecutar el mio en mi Laptop.<br>

![biblioteca dinamica](https://user-images.githubusercontent.com/113700163/190681324-253d8dae-277b-4952-a057-99a030dbd9d8.png)<br>

como pudimos observar a la hora de ejecutar el .exe de mi compañero, salio en la primera linea su nombre y en la segunda mi nombre y esto se debe porque a la hora de compilar le estamos diciendo al compilador que el archivo foo.ccp lo convierta como biblioteca compartida con PIC y y se guarde en el archivo foo.dll.<br>

aqui les comparto los archivos que se crearon [carpetas_Compartidas_y_Estaticas.zip](https://github.com/MarioAzael65/programacion-de-sistemas/files/9604004/carpetas_Compartidas_y_Estaticas.zip)<br>

### Programamos en phyton

la mestra nos pidio que ingresaramos al canal de la [facultad de matematicas de la uv](https://www.youtube.com/channel/UC6WEQBcRCG8ZYA0qkV2hi4g) donde venian varios vides donde nos mostraba como usar python con algunos ejemplos y hacia de uso la pagina [Clandestina-hds](https://clandestina-hds.com/cursoPyQT5/index.html)<br>

