# -1<sup>er</sup>proyecto: Encendidos alternativos. 

<p align="center">
<img src= "Imágenes/arduino_led.png" width="600" height="500" />
</p>

## Explicación del circuito:

Lo que tiene que hacer el circuito es que cuando se encienda los diodos leds se esten encendiendo y apagando por separado lo mas rapido posible.

## Codigo:

<p align="center">
<img src= "Imágenes/Captura de pantalla 2025-11-02 215253.png" width="200" height="300" />
</p>

Mi codigo comienza con el void sutup (sirve para ejecutar un bloque de código una sola vez al inicio del programa),
continua con el  pinMode(8, OUTPUT); y pinMode(7, OUTPUT); (lo que hace esto es que el pin que este seleccionado sea de salida.
El programa continua con un void loop() (se usa para crear un bucle), el digitalWrite(8, HIGH) se usa para establecer un pin digital en estado alto (HIGH) y bajo (LOW) , despues el otro pin digitalWrite(7, LOW) lo ponemos bajo, usamos un delay(120) para que cuando se use el primer programa haya un tiempo de espera de 120 milisegundo. Despues el lo mismo pero intercambiando el low por el high y fin del programa.



# -2<sup>er</sup>proyecto: Pulsador. 

<p align="center">
<img src= "Imágenes/PULSADOR.png" width="600" height="500" />
</p>

## Explicación del circuito:
El objetivo del circuito es que cuando el programa se ponga en marcha un diodo led se encienda y cuando pulsemos el pulsador el que esta encendido se apague y el otro se encienda mientras que este pulsado.


## Codigo:
<p align="center">
<img src= "Imágenes/Captura de pantalla 2025-11-02 215541.png" width="300" height="400" />
</p>

Al empezar el código creamos 4 variantes, que se crea con el comando __int__ (funciona creando un nombre para esa variable y poder utilizarlo duranto todo el codigo).

Hemos creado dos variables para los dos leds llamadas __LED7__ y __LED8__.

Otra para el pulsador llamada __pulsador__.

Y por ultimo la variante para el valor que nos salga llamada __valor2__.
 
Dentro del __void setup__ usamos 3 __pinmode__ uno del __pulsador__ que lo ponemos de __entrada__  y los otros dos son de los __led 7 y 8__ que lo ponemos como salida.

El __serial.begin(9600)__ es la velocidad de transmision en bits por segundo para que el arduino pueda enviar y recibir datos.

Sigue con el __void loop__ de primeras tenemos que el __valor2 = digitalwrite(pulsador)__ (esto significa que el valor2 va a ser igual al del pulsador. A continuación usamos el __if__ (compararor) y le preguntamos si el __valor2 = high__ (si el valor2 esta encendido) el __digitalWrite(LED7, LOW)__ y el __digitalWrite(LED8, HIGH)__ (lo que le preguntamos aqui es que si el valor2 esta encendido el led 7 esta apagado y el led 8  encendido), 
y abajo es lo mismo pero al reves.

# -3<sup>er</sup>proyecto: Potenciometro. 


<p align="center">
<img src= "Imágenes/Captura de pantalla 2025-11-02 215725.png" width="600" height="500" />
</p>


# -4<sup>er</sup>proyecto: Mapeado de potenciometro. 

<p align="center">
<img src= "Imágenes/potenciómetro_real (1).jpg" width="400" height="400" />
</p>

## Codigo:
<p align="center">
<img src= "Imágenes/mapeado_potenciometro (1).png" width="800" height="700" />
</p>



# -5<sup>er</sup>proyecto: Ultrasonido.

<p align="center">
<img src= "Imágenes/Ultrasonido.jpg" width="500" height="500" />
</p>

## Codigo:

<p align="center">
<img src= "Imágenes/mapeado_ultrasonic.png" width="400" height="400" />
</p>
