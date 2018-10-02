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

![captura 2](https://user-images.githubusercontent.com/43210622/46337298-d4ef2500-c5f2-11e8-8172-48436c6cb796.PNG)

Se establecen los pines de la placa LCD y se cran las variables de salida
para el buzzer y los diodos led (rojo y verde). Se establecen 4 filas, 4 columnas.
Se define la matriz del teclado (keymap.
Se conectan los keypads ROW1, ROW2, ROW3 y ROW4 a esos Pines de Arduino, ( 9,8,7,6 )
y  los keypads COL1, COL2, COL3 y COL4 a esos Pines de Arduino ( 5,4,3,2,).

![captura 3](https://user-images.githubusercontent.com/43210622/46353209-3d54fb00-c621-11e8-99f8-ec902ff8f04e.PNG)

La siguiente imagen se muestra los componentes ya montados en la protoboard
donde en la pantalla display nos muestra el mensaje *Bienvenido* FAVOR ENTRE PIN.

![captura 4](https://user-images.githubusercontent.com/43210622/46353845-c3be0c80-c622-11e8-9e50-55e152a5ca6a.PNG)

Una vez ingresado el PIN correcto, nos mostrara el siguiente mensaje & el led verde se mostrara encendido.

![captura 5](https://user-images.githubusercontent.com/43210622/46353995-18fa1e00-c623-11e8-9de5-84f6aee90308.PNG)

En caso de que la clave PIN sea incorrecta, nos mostrará el mensaje que se señala en la siguiente
imagén, y el led rojo se mantendra encendido.














