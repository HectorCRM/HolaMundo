# C++ 💻
## Un poco de historia 📚
**C++** es un lenguaje de programación creado en **1979** por [**Bjarne Stroustrup**](https://es.wikipedia.org/wiki/Bjarne_Stroustrup), en los Laboratorios Bell. Aunque no fue hasta **1983** que fue bautizado con el nombre que lo conocemos hoy día, ya que hasta entonces se lo llamaba ***C con clases***. Fue uno de los compañeros de **Bjarne Stroustrup**, **Rick Mascitti**, quien propuso el nombre de **C++**.  
Fue creado como una extensión de **C** para dotarlo de **POO**. Es un lenguaje multiparadigma, puesto que permite programación generica, programación estructurada y POO. 
Destaca por ser un lenguaje que otorga un gran control sobre el hardware y los recursos del sistema, siendo ideal para videojuegos, sistemas operativos, software de alto rendimiento y aplicaciones gráficas, destacando por su velocidad, aunque también por su complejidad.  
Como curiosidad, **C++** es el lenguaje que se utiliza en programación de microcontroladores(Arduino's, ESP32...) en el **IDE de Arduino**.

## Sobre Bjarne Stroustrup :man:
[**Bjarne Stroustrup**](https://es.wikipedia.org/wiki/Bjarne_Stroustrup) nació el 30 de Diciembre de 1950 en Aarhus, Dinamarca. Se crió en el seno de una familia de clase trabajadora, asistiendo a colegios locales. Asistió a la Universidad de Aarhus entre 1969 y 1975, donde se graduó *Candidatus Scientiarum* en matemáticas con informática, un titulo establecido en la Unión Soviética y que fue adoptado por muchos países de Europa central y del Este, equivalente a una maestría. En 1979 obtuvo un doctorado en informática por la Universidad de Cambridge, tras lo cual comenzó su carrera en el Centro de Investigación en Ciencias de la Computación de Laboratorios Bell. Fue entonces cuando comenzó a trabjar en C++.  
[Bjarne Stroustrup, Wikimeadia Commons](./images/Bjarne-stroustrup_(cropped).jpg)  

Entre 2002 y 2014 fue profesor de Ingeniería en Ciencias de la Computación en la Universidad de Texas, desde 2011 fue nombrado Profesor Distinguido de dicha Univiersidad.  
Desde Enero de 2014 hasta Abril de 2022 fue investigador técnico y director general de la división de tecnología de Morgan Stanley y profesor visitante de informática en la Universidad de Columbia.  
Desde 2022 es profesor titular de Informática en la Universidad de Columbia.  
Es autor de varios libros:  
 - *The Annotated C++ Reference Manual*, del año 1990.  
 - *The Design and Evolution of C++*, del año 1994.  
 - *The C++ Programming Language*, del año 2000.  
 - *Programming -- Principles and Practice Using C++*, del año 2008.  
 
Bjarne Stroustrup tiene una gran cantidad de premios y distinciones(la lista es larga, pero puedes verlo [aquí](https://www.stroustrup.com/bio.html)). También tiene en su haber dos doctorados *honoris causa*: Por la universidad Carlos III de España en 2019 y por la Universidad ITMO en 2013.

## Hola mundo! 🖖
Vamos a hacer nuestro "Hola mundo" desde la terminal. En Fedora g++, el compilador para C++, viene instalado por defecto. Podemos comprobarlo con:  
```
g++ --version
```
Nos dará un resultado así, si lo tenemos instalado:  
![g++ version](https://github.com/HectorCRM/HolaMundo/blob/main/Lenguajes/C%2B%2B/images/Snapshot_2025-12-09_20-46-33.png)  
Hecho esto ya podemos programar nuestro "Hola mundo" en C++. Crearemos un archivo de texto con extension ***.cpp***:  
```
nano Hola.cpp
```
Y escribimos el siguiente código:
```
#include <iostream>
using namespade std;
int main(){
  cout << "Hola mundo!" <<endl;
  return 0;
}
```
Ahora compilamos y le damos nombre:  
```
g++ Hola.cpp -c HolaMundo
```
Ya podemos ejecutar nuestro programa!:
```
./HolaMundo
```
Resultado:  
![Proceso completo](https://github.com/HectorCRM/HolaMundo/blob/main/Lenguajes/C%2B%2B/images/Snapshot_2025-12-09_20-50-16.png)

## Requisitos
-Ordenador  
-Editor de textos  
-G++ instalado en el sistema operativo
## Autor 👨‍🎓
**Héctor Monroy Fuertes** - Estudiante de DAM. 

