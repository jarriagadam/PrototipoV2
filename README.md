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
