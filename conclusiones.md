Una vez visto por encima este robot, queremos comentar los inconvenientes que vemos:

##BATERIA
Que se haga por software el apagado es un gran inconveniente, pues si no se hace (y sospechamos que por comodidad no se hará) PERJUDICA A LA VIDA ÚTIL DE LA BATERÍA ¿qué les costaba poner un micro-interruptor?
##SENSOR DATA
El registro de posición, velocidad y giro es tentador para hacer experimentos STEAM con él de dinámica pero ... EL SENSOR DE POSICIÓN Y VELOCIDAD SE REALIZA POR EL MOTOR PASO A PASO INTERNO DEL ROBOT ¿qué quiere decir esto? pues que mide la distancia y velocidad cuando **hacemos mover el robot por software**

Prueba: El siguiente ejemplo movemos nosotros el robot externamente, y vemos que el sensor detecta sólo que lo hemos movido menos de 2cm ¿por qué? porque **no ha rodado**

{% youtube %}https://www.youtube.com/watch?v=3d1ckVvrsIc&feature=youtu.be{% endyoutube %}

Este es el resultado:

![](/assets/2019-10-27 10_27_23-Window.jpg)

##FALTA PROGRAMACIÓN BIDIRECCIONAL APP-SPHERO MINI
El robot se comunica con la app (con algo de retraso por el Bluetooth) envía los datos de los sensores...

##Lo que sí que nos gusta
* Ocupa poco
* Buen diseño
* Es muy resistente a golpes.
