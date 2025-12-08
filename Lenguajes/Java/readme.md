# Java
## Un poco de historia
Java es un lenguaje de programación creado en **1991** por [**James Gosling**](https://es.wikipedia.org/wiki/James_Gosling) para [**Sun Microsystems**](https://es.wikipedia.org/wiki/Sun_Microsystems) y publicado en **1995**.  
El proyecto, denominado ***The Green Project***, fue desarrollado en 18 meses por un equipo de trece personas dirigidas por **James Gosling**.  
Como curiosidad, el lenguaje desarrollado por el equipo en un principio se denominó ***Oak**, por un roble que se veia desde la oficina de **James Gosling**. Mas tarde paso a llamarse ***Green*** y al final acabo llamandose como lo conocemos hoy día.  
Otra curiosidad es que los cuatro primeros bytes de los archivos ***.class*** que genera el compilador son en hexadecimal **0xCAFEBABE**, se ve que al equipo le gustaba el café.  

La sitnaxis de java deriva de **C/C++**, pero con menos utilidades de bajo nivel que ellos.  
El **bytecode** generado al ser compilado se puede ejecutar en cuqluier ***maquina virtual java(JVM)***, sin importar la arquitectura subyacente.

## Hola mundo!
Vamos a hacerlo desde terminal, en mi caso utilizo Fedora.
Abrimos una terminal y escribimos lo siguiente:
```
nano Hola.java
```
Después escribimos nuestro pequeño programa para que diga **Hola mundo!** y guardamos:
```
public class Hola {
        public static void main(String[] args) {
                System.out.println("Hola mundo!");
        }

}
```
Al volver a la terminal ya podemos compilar el archivo para generar el ***bytecode***
```
javac Hola.java
```
Y ahora ya podemos ejecutarlo:
```
java Hola
```
Resultado:  



## Requisitos
-Un ordenador, o incluso se puede hacer en un smartphone Android si tienes instalado ***Termux***.
-JDK instalado en el sistema operativo
## Autor 👨‍🎓
**Héctor Monroy Fuertes** - Estudiante de DAM. 
