# C [![My Skills](https://skillicons.dev/icons?i=c)](https://skillicons.dev)
## Un poco de historia 📚
**C** es un lenguaje de programación creado entre **1969** y **1973** en los Laboratorios Bell por [**Dennis Ritchie**](https://es.wikipedia.org/wiki/Dennis_Ritchie), como una evolucion de **B**.  
Es un lenguaje orientado a su implementación en sistemas operativos Unix, debido a que dispone de de estructuras tipicas de lenguajes de alto nivel, pero, al mismo tiempo, tambien dispone de estructuras de bajo nivel que permiten mezclar codigo **C** con **Ensamblador** y acceder directamente a memoria o perifericos.  
 

## Hola mundo! 🖖
Vamos a hacer nuestro "Hola mundo" desde la terminal. En Fedora **gcc**, el compilador para **C**, viene instalado por defecto. Podemos comprobarlo con:  
```
gcc --version
```
Nos dará un resultado así, si lo tenemos instalado:  
![gcc version](https://github.com/HectorCRM/HolaMundo/blob/main/Lenguajes/C/images/Snapshot_2025-12-10_12-27-09.png)  
Hecho esto ya podemos programar nuestro "Hola mundo" en C. Crearemos un archivo de texto con extension ***.c***:  
```
nano Hola.c
```
Y escribimos el siguiente código:
```
#include <stdio.h>
int main() {
	printf("Hola mundo!\n");
	return 0;
}
```
Ahora compilamos y le damos nombre:  
```
gcc Hola.c -c HolaMundo
```
Ya podemos ejecutar nuestro programa!:
```
./HolaMundo
```
Resultado:  
![Proceso completo](https://github.com/HectorCRM/HolaMundo/blob/main/Lenguajes/C/images/Snapshot_2025-12-10_12-28-40.png)

## Requisitos
-Ordenador  
-Editor de textos  
-Gcc instalado en el sistema operativo
## Autor 👨‍🎓
**Héctor Monroy Fuertes** - Estudiante de DAM. 

