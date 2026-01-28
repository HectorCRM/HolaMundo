# C# [![My Skills](https://skillicons.dev/icons?i=cs)](https://skillicons.dev)
## Un poco de historia 📚
**C#** o **C Sharp** es un lenguaje de programación publicado en el año **2000** por un equipo formado por [**Anders Hejlsberg**](https://es.wikipedia.org/wiki/Anders_Hejlsberg) para Microsoft, para dotar de orientación a objetos a la plataforma **.NET**.  
Su sintaxis deriva de **C** y **C++** y utiliza el modelo de objetos similar al de **Java**.  
Como curiosidad, el simbolo **# o sharp**, se traduce en notación musical como sostentido, es decir, que la nota en cuestión debe sonar un semitono más alta que su versión normal(su predecesor **C++** en este caso). Es una metafora de la superioridad de **C#** sobre **C++**. Además, en simbolo **#** puede ser imaginado como cuatro simnbolos **+**.  

 
## Hola mundo! 🖖
Vamos a hacer nuestro "Hola mundo" desde la terminal. En esta ocasion el compilador para **C#** no viene instalado por defecto en Fedora, quizas en Windows si al ser un lenguaje creado por Microsoft. Podemos instalarlo con el siguiente comando, segun el gestor de paquetes de cada distro:  
```
sudo (dnf/apt/yum/pacman) install mono
```  
Con esto ya podemos programar y compilar nuestro **"Hola mundo!"** en **C#**.   
A continuación crearemos un archivo de texto con extension ***.cs***:  
```
nano Hola.cs
```
Y escribimos el siguiente código:  
```
using System;
public class Hola {
	public static void Main(string[] args) {
		Console.WriteLine("Hola mundo!");
	}
}
```
Ahora compilamos con **msc** y le damos nombre:  
```
msc Hola.cs -o HolaMundo
```
Ya podemos ejecutar nuestro programa!:
```
mono HolaMundo
```
Resultado:  
![Proceso completo](https://github.com/HectorCRM/HolaMundo/blob/main/Lenguajes/C%23/images/Snapshot_2025-12-12_11-19-45.png)

## Requisitos
-Ordenador  
-Editor de textos  
-Mono instalado en el sistema operativo  
## Autor 👨‍🎓
**Héctor Monroy Fuertes** - Estudiante de DAM. 

