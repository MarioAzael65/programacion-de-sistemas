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
### ¿Que es una biblioteca dinamica?
Una biblioteca dinámica es aquella que se carga a la hora de arrancar un programa. A diferencia de las bibliotecas estáticas, las bibliotecas dinámicas utilizan recursos independientes al ejecutable que las llama. Es decir, una biblioteca dinámica no es copiada al programa durante el proceso de compilación. Así, durante la ejecución de nuestro programa, en el momento en el que este necesite recursos de las bibliotecas, este los buscará en ellas. En el supuesto de que se borrase la biblioteca, el programa daría un error al no poder encontrarla.<br>
#### Actividad de biblioteca estatica y dinamica
En la practica la maestra nos compartio un PDF por teams donde venian las instrcuciones de lo que deberiamos hacer, para ver como funcionanban estas bibliotecas. y que pasaba si solo se compartia el archivo .exe con otro compañero.<br>
con la <strong>biblioteca estatica</strong> esto fue lo que ocurrio al ejecutar el .exe.<br>
![ejemplo de biblioteca estatica!](![biblioteca estatica](https://user-images.githubusercontent.com/113700163/190680485-773bac7a-17c0-400c-8eb6-77a1e524dcd1.png)<br>
con la <strong>biblioteca dinamica </strong> comparti el archivo con mi compañero Juan y el compartio su archivo conmigo y esto fue lo que me salio al ejecutar el archivo.<br>
![ejemplo de bilioteca dinamica compartida!](![biblioteca dinamica juan](https://user-images.githubusercontent.com/113700163/190681078-bd732e24-0567-4360-a5a6-a32e61089762.png)
esto es lo que aparecio al ejecutar el mio en mi Laptop.<br>
![ejemplo de blioteca dinamica!](![biblioteca dinamica](https://user-images.githubusercontent.com/113700163/190681324-253d8dae-277b-4952-a057-99a030dbd9d8.png)


)
