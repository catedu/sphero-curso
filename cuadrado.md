#Cuadrado

###Objetivo
Un programa que mueva a Sphero Mini en un cuadrado 10cm x 10 cm y visualizaremos el resultado en el registro de sensores del mismo programa.

##Programa
Este programa el truco está en hacer un bucle que mueva el robot hasta que la posición de la ordenada sea 10 cm, orientamos el sphero-mini y a por el siguiente lado. Total 4 bucles.

El programa lo puedes encontrar en este enlace

https://edu.sphero.com/remixes/5450219

![](/assets/2019-10-20 13_33_22-Window.jpg)

##Sensor data

Una vez ejecutado, podemos ir al registro de los sensores:

![](/assets/2019-10-20 13_37_13-Window.jpg)

y la verdad es que del diseño 10cm x 10cm, ha salido un cuadrado un poco .... vamos que el error es casi del 70%

![](/assets/2019-10-20 13_38_51-Window.jpg)

Pero **los sensores SI que miden bien**, lo puedes ver en el vídeo:

##Resultado

{% youtube %}https://youtu.be/YxkXVzXxxsE{%endyoutube%}

##¿Por qué es tan impreciso?
Ya te dimos una pista en [Giro-mensaje](/giro-mensaje.md): La comunicación entre la aplicación y el robot, cuando la aplicación manda el mensaje de que gire y haga el otro lado, ese retardo él ya ha recorrido 7cm.


