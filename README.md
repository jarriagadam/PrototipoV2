¡Hola a todos! Necesito ayuda en programación de Arduino. Estoy haciendo un control bluetooth con luces y sonidos. Varias de las funciones del control ya funcionan, pero me quedan algunas que no he podido resolver. Estoy seguro de que alguien entendido en Arduino podría resolverlas fácilmente.
Estas son las funciones del control:
•	PRESIONAR BOTÓN y 
•	Activar luz RGB Neopixel al presionar botón. (Por ejemplo, rojo al presionar botón rojo). 
•	Activar sonido con módulo mp3 (YX5300) al presionar botón. Debe activarse un archivo especifico. Ejemplo 004.mp3. *Actualmente tengo el código que permite activarlo usando el monitor serial. Digito P04 y se reproduce perfectamente.

•	PRESIONAR BOTÓN y Activar lectura RFID  Al presionar el botón, se inicializa el modulo RFID para que espere una nueva tarjeta.

•	LEER TARJETA RFID y 
•	Activar luz RGB al leer un tag especifico. Ejemplo: Rfid lee el tag 04 06 XF y activa color Morado RGB. *Actualmente tengo el código del RFID que me entrega los valores, pero necesito que ese valor lo interprete igual que si fuera un botón.
•	Activar sonido con módulo mp3 (YX5300). Igual que en botón.

•	PRESIONAR SW ROTARY ENCODER Y 
•	Activar animación luz RGB. *Tengo este código.
•	Activar sonido modulo mp3. *Necesito integrarlo al código anterior.
Consideraciones importantes: La idea es poder combinar estos códigos en uno solo y así poder integrarlas al control.
Los archivos de este proyecto los subiré a Github para que puedan descargarlos y analizarlos.
Muchas gracias!

------------------------------------------------------------------------------------------------------------

Hi everyone! Thanks for the help in the previous post.
Right now, I am trying to figure out some solutions for my Arduino code. As you guys may know I am building a Bluetooth controller with lights and sound. 
These are the things I need help with:
•	PRESS BUTTON and --->
•	Activate RGB Neopixel light when button is pressed. For example, turn red when button red is pressed.
•	Activate sound from mp3 module (YX5300) when pressing button. The module plays a specific sound file. For example: 004.mp3. *I have the code that activates sound with serial monitor but I don´t know how to assign that print to the push button. If I press “P04” it plays the file.

•	PRESS BUTTON and start RFID --->
•	When specific button is pressed the RFID starts reading.

•	READ A RFID TAG and --->
•	Activates RGB light when a specific tag is scanned. Example: RFID reads tag 04 06 XF and activates Purple RGB. * I have the code that reads any tag from the RFID NFC.
•	Activate sound file with mp3 module (YX5300) just like push button.
•	PRESS ROTARY ENCODER BUTTON and --->
•	Activate RGB light animation that changes each time I press Rotary Encoder button SW. *I have this code working
•	Activate mp3 sound when encoder button is pressed. Same as before.
It´s really important that these codes can be combined into one so that I can upload it to the Arduino.
I will leave all the code examples in Github link and also my Arduino Pins.
https://github.com/jarriagadam/PrototipoV2/

Thanks guys!
