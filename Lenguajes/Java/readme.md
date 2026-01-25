# Java ☕
## Un poco de historia
Java es un lenguaje de programación creado en **1991** por [**James Gosling**](https://es.wikipedia.org/wiki/James_Gosling) para [**Sun Microsystems**](https://es.wikipedia.org/wiki/Sun_Microsystems) y publicado en **1995**.  
El proyecto, denominado ***The Green Project***, fue desarrollado en 18 meses por un equipo de trece personas dirigidas por **James Gosling**.  
Como curiosidad, el lenguaje desarrollado por el equipo en un principio se denominó ***Oak***, por un roble que se veía desde la oficina de **James Gosling**. Mas tarde paso a llamarse ***Green*** y al final acabo llamandose como lo conocemos hoy día.  
Otra curiosidad es que los cuatro primeros bytes de los archivos ***.class*** que genera el compilador son en hexadecimal **0xCAFEBABE**, se ve que al equipo le gustaba el café.  

La sitnaxis de java deriva de **C/C++**, pero con menos utilidades de bajo nivel que ellos.  
El **bytecode** generado al ser compilado se puede ejecutar en cuqluier ***maquina virtual java(JVM)***, sin importar la arquitectura subyacente.  

## Sobre James Gosling :man:
[**James Gosling](https://es.wikipedia.org/wiki/James_Gosling) nació el 19 de mayo de 1955 en Calgary, Canadá. Desde muy joven mostró un gran interes por la informática y la tecnología, creando sus propios dispositivos electrónicos. Esto le llevo a profundizar en el mundo de la programación.  
Estudió Cincias de la Computación en la Universidad de Calgary, destacando por su habilidad para resolver problemas complejos. Tras su licenciatura en 1977, decidió continuar sus estudios en la Universidad Carnegie Mellon, donde, en 1983, se doctoró en Ciencias de la Computación.  
![James Gosling, 2008. WikiMedia Commons](./images/James_Gosling_2008.jpg)
En 1984 Gosling comenzó su carrera en Sun Microsystems. En 1990 la compañia inicio un nuevo proyecto llamado  **The Green Project**, cuyo objetivo era desarrollar un sistema operativo para dispositivos inteligentes. El problema con que se encontraron fue que cada fabricante tenia hardware y sistemas operativos diferentes, lo que complicaba enormemente la creación de aplicaciones universales. A raiz de este problema Gosling creó Java, siendo publicado oficialmente en 1995.  
En 2010 Sun Microsystems fue comprada por Oracle y al tener estrategias diferentes para Java, Gosling decició abandonar Oracle. Tras abandonar Oracle pasó a trabajar en Google en 2011. Posteriormente, entre 2011 y 2017, fue jefe de arquitectura en Liquid Robotics.  
Su ultimo empleo fue en AWS entre 2017 y 2024 cuando se retiró.  

James Gosling ha obtenido varios premios y reconocimientos a lo largo de su carrera. Algunos de ellos son:  
 - Premio USENIX Flame, 2002.  
 - The Economist Innovation Award, 2002.  
 - Premio ACM Software System, 2002.  
 - Premio Tsutomu Kanai, 2003.  
 - Miembro de la National Academy of Engineering, 2004.  
 - Oficial de la Orden de Canadá, 2007.  
 - Miembro de la Asociación de Maquinaria Computacional, 2013.  
 - Medalla IEEE John Von Neumann, 2015.  
 - Miembro del Computer History Museum Felow, 2019.  


 

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
![imagen](https://github.com/HectorCRM/HolaMundo/blob/main/Lenguajes/Java/images/Snapshot_2025-12-09_00-31-13.png)


## Requisitos
-Un ordenador, o incluso se puede hacer en un smartphone Android si tienes instalado ***Termux***.  
-JDK instalado en el sistema operativo
## Autor 👨‍🎓
**Héctor Monroy Fuertes** - Estudiante de DAM. 
