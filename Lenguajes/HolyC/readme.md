# C† [HolyC] (./images/HolyC_Logo_escalado.png)
## Un poco de historia 📚
**C†** o **HolyC** es un lenguaje de programación creado por **Terry A. Davis** para escribir su propio sistema operativo, [**TempleOS**](https://templeos.org/). HolyC deriva de C y fue desarrollado por Davis entre **2003** y **2014**. Lo desarrolló con modificaciones para hacerlo más simple que C, e integrado con el hardware, él mismo lo describía como un lenguaje recreativo  y divertido, enfocado en la programación de bajo nivel sin complicaciones modernas.  
Su sintaxis es similar a la de C, usando estructuras de C pero con extensiones. Por ejemplo las cadenas *"ejemplo"*, actúan como llamadas a *printf* automáticamente. C† se compila en tiempo de ejecución(Just-In-Time). La extensión de los archivos de código de C† es **.HC**.  

## Sobre Terry A. Davis :man: 
***Terrence Andrew Davis*** nació el 15 de diciembre de 1969 en West Allis, en el condado de Milwaukee, Wisconsin. Fue el séptimo de ocho hermanos. De niño tuvo un AppleII y una Commodore 64, gracias a lo cual aprendió lenguaje ensamblador. Entre 1990 y 1996 trabajó como programador de máquinas VAX para TicketMaster. Más tarde, en 1994, obtendría una maestría en ingeniería eléctrica por la Universidad Estatal de Arizona.   
[Terry, últimos años](./images/TerryB&W.jpeg)  
  

En el año 1996 comenzó a sufrir episodios maníacos y delirios con extraterrestres y agentes gubernamentales que lo perseguían, lo que hizo que fuera hospitalizado por problemas de salud mental. Más adelante, en uno de estos episodios creyó que la radio de su coche le estaba hablando y condujo cientos de kilómetros al sur de su destino, donde abandonó su coche en pleno desierto de Texas. Un agente de policía lo recogió y lo llevó al hospital donde, en un principio, le diagnosticaron trastorno bipolar, aunque más adelante fue diagnosticado con esquizofrenia paranoide.  
Debido a su diagnóstico de esquizofrenia paranoide, quedó desempleado por el resto de su vida, teniendo que vivir con sus padres recibiendo una pequeña pensión de la Seguridad Social.  
Terry creció en un hogar católico, aunque al tiempo dejase la fe de lado y se hiciese ateo. Fue en torno a 2003 cuando tuvo una supuesta "revelación", tras la cual proclamó que estaba en comunicación directa con Dios y que este le había pedido que construyera su *tercer templo*. Este tercer templo no sería de ladrillos ni piedra, se construiría con 0 y 1. Fue así como Terry empezó a desarrollar **TempleOS**, cuyo primer nombre fue **J Operating System**, después pasaría a llamarse **LooseThos** para más tarde llamarlo **SparrowOS**. Su último nombre sería por el cual lo conocemos hoy día **TempleOS**.  
Esta revelación hizo que un sólo hombre crease desde cero lo que normalmente requiere grandes equipos de desarrollo: escribió +100.000 lineas de código para crear TempleOS en su propio lenguaje de programación, HolyC.  
En sus últimos años de vida Terry decidió donar todo su dinero y pertenencias a la caridad, lo que hizo que la mayor parte del tiempo de sus ultimos años tuviese que vivir en su coche.  
Terry A. Davis falleció el 11 de Agosto de 2018, atropellado por un tren en The Dalles, Oregón, a la edad de 48 años.  

## Hola mundo! 🖖
Si nunca antes has cacharreado con templeOS esto es lo primero que verás al iniciarlo:  
[Pantalla inicio TempleOS](./images/Menu_iniciotempleOS.png)  
En la captura no se puede apreciar, pero todo parpadea continuamente. Es un sistema operativo totalmente diferente a cualquier otro.  
Para ver mejor cierra la pequeña ventana guia de la derecha (boton esquina superior derecha [x]), tras esa ventana está la terminal. Yo ya tenía creada una carpeta de la última vez que estuve cacharreando con TempleOS, pero no es necesario para nuestro **"Hola mundo!"**.  
Vamos a crear un archivo de texto para imprimir por terminal el mensaje, para ello escribe:  
```
Ed("Hola.HC");
```
[Ed](./images/mensaje_en_Ed.png)
Pero ojo, los carácteres del teclado no coincidirán. En el siguiente cuadro de texto dejo a la izquierda el caracter del teclado español y a la derecha su equivalencia:  
```
**(** = shift+9
**"** = shift+{(tecla a la derecha de la ñ)
**)** = shift+0
**:** = ñ
```
Sigamos. Una vez abierto ***Ed***, el editor de textos, simplemente escribiremos:  
```
"Hola Mundo!"
```
Ya está, nada más. Pulsamos F5 para compilar y ejecutar:  
[resultado](./images/resultado.png)  

## Requisitos
-Maquina virtual con [**TempleOS**](https://templeos.org/) instalado.  


## Autor 👨‍🎓
**Héctor Monroy Fuertes** - Estudiante de DAM. 

