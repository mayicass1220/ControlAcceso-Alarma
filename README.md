## TECNOLÓGICO NACIONAL DE MÉXICO
### INSTITUTO TECNOLÓGICO DE LEÓN
INGENIERÍA EN SISTEMAS COMPUTACIONALES
#### MATERIA:
Sistemas Programables
#### ControlAcceso-Alarma
Control de Acceso a Puertas con Clave y Display LCD
#### PRESENTA:
Casillas Manrique Mariela Abigail
#### PROFESOR:
Ing. Levy Rojas Carlos Rafael
#### HORARIO:
Martes & Jueves 8:45 - 10-25 am



### INTRODUCCIÓN
Para própositos de está práctica, se creó el sgiguiente proyecto el cual consite en un programa
para poder acceder a una puerta, este sistema será gestionado por una clave que nos permitira o 
denegara el acceso. Se explica tambiém paso a paso como programar Arduino para permitir el 
Control de Acceso a una puerta a través de una Clave o PIN de acceso.

### MATERIALES
Para el desarrollo de este proyecto se listan a continuación lo materiales necesarios para su 
desarrollo.
1. Protoboard
2. Placa Arduino UNO 
3. Display LCD 16x2
4. Teclado matricial (keypad) 4x4
5. Dos diodos LED (rojo/verde)(2 resistencias 330 Ohm)
6. Buzzer pasivo
7. Cables Dupont macho/hembra.
8. Un potenciometro de 10k

### DESARROLLO
En la siguiente imagen se muestra el diagrama, que muestra la 
conexión y diseño utilizado para este proyecto.
![alarma_diagrama_opt](https://user-images.githubusercontent.com/43210622/46336144-8ab87480-c5ef-11e8-9b26-19d2a9830f64.png)

Procedemos con la programación 
Comenzando por incluir las librerias necesarias 

![captura 1](https://user-images.githubusercontent.com/43210622/46337079-4da1b180-c5f2-11e8-9211-1bae951e4182.PNG)

Se define la clave o contraseña que nos dará el acceso, así como la longitud de 
caractéres de la misma.


