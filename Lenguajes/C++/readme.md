# C++ [![My Skills](https://skillicons.dev/icons?i=cpp)](https://skillicons.dev)
## Un poco de historia 📚
**C++** es un lenguaje de programación creado en **1979** por [**Bjarne Stroustrup**](https://es.wikipedia.org/wiki/Bjarne_Stroustrup), en los Laboratorios Bell. Aunque no fue hasta **1983** que fue bautizado con el nombre que lo conocemos hoy día, ya que hasta entonces se lo llamaba ***C con clases***. Fue uno de los compañeros de **Bjarne Stroustrup**, **Rick Mascitti**, quien propuso el nombre de **C++**.  
Fue creado como una extensión de **C** para dotarlo de **POO**. Es un lenguaje multiparadigma, puesto que permite programación generica, programación estructurada y POO. 
Destaca por ser un lenguaje que otorga un gran control sobre el hardware y los recursos del sistema, siendo ideal para videojuegos, sistemas operativos, software de alto rendimiento y aplicaciones gráficas, destacando por su velocidad, aunque también por su complejidad.  
Como curiosidad, **C++** es el lenguaje que se utiliza en programación de microcontroladores(Arduino's, ESP32...) en el **IDE de Arduino**.

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
using namespace std;
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

