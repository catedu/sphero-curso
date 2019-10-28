#Malabares

###Objetivo
Un programa que al lanzar el mini emita un sonido y al aterrizar otro efecto de sonido-luminoso

##Programa
Cogeremos los eventos de "caída libre" y "aterrizaje" haremos unos efectos distintos en cada caso. Son eventos que responden al sensor de aceleración en el eje vertical (en caída libre tendrá un valor nulo después de pasar por un máximo y en aterrizaje será un valor máximo después de pasar por un valor nulo)
El programa lo puedes encontrar en este enlace

https://edu.sphero.com/remixes/5451292

![](/assets/2019-10-20 13_00_41-Sphero Edu.jpg)

##Resultado

{% youtube %}https://youtu.be/Wo6s6GsECEs{%endyoutube %}

##¿Por qué a veces no se sincroniza el movimiento con el sonido?
Si nos fijamos, dependiendo de nuestro equipo (ordenador o móvil) hay un retraso en la comunicación Bluetooth, que hace que el efecto no está sincronizado con el evento.