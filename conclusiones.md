Una vez visto por encima este robot, queremos comentar las principales ventajas/inconvenientes que vemos en este robot. Son opiniones nuestras que valoramos desde CATEDU y son totalmente criticables y perfectamente puedes no estar acuerdo o [ponerte en contacto con nosotros](http://soporte.catedu.es/) si ves que tendríamos que cambiar algo:

##BATERÍA: PUNTO CRÍTICO DE ESTE ROBOT
Que se haga por [software el apagado](/pros-and-cons.md) es un gran inconveniente, pues si no se hace (y sospechamos que por comodidad no se hará) PERJUDICA A LA VIDA ÚTIL DE LA BATERÍA ¿qué les costaba poner un micro-interruptor? y además no es fácil su sustitución.

##SENSOR DATA NO VALE PARA EXPERIMENTOS DE CINEMÁTICA.
El registro de posición, velocidad y giro es tentador para hacer experimentos de dinámica-cinemática STEAM con el robot pero ... EL SENSOR DE POSICIÓN Y VELOCIDAD SE REALIZA POR EL MOTOR PASO A PASO INTERNO DEL ROBOT ¿qué quiere decir esto? pues que mide la distancia y velocidad cuando **hacemos mover el robot por software** pues es casi imposible que el robot *ruede internamente* por impulso externo. 

Prueba el siguiente ejemplo: lanzar Sphero por una superficie. Vemos que el sensor detecta sólo que lo hemos movido menos de 2 cm. ¿Por qué? porque **no ha rodado internamente** excepto al final en el breve frenado:

{% youtube %}https://www.youtube.com/watch?v=3d1ckVvrsIc&feature=youtu.be{% endyoutube %}

Este es el resultado:

![](/assets/2019-10-27 10_27_23-Window.jpg)

##FALTA PROGRAMACIÓN BIDIRECCIONAL: APP SPHERO EDU ↔ ROBOT SPHERO MINI
El robot se comunica con la app (con algo de retraso por el Bluetooth) envía los datos de los sensores... luego hay comunicación entre Sphero-mini y la APP pero **sólo en un sentido Sphero-Mini ➡ Aplicación** ¿Por qué no existe el otro sentido Sphero-mini ⬅ Aplicación? 

Por ejemplo en [Sphero Play](/primer-contacto.md) hay juegos que utilizan el móvil como joystick, pero en [Sphero Edu](/segundo-programar.md) no podemos programar enviar órdenes a Sphero-mini, por ejemplo usar las teclas del teclado como joystick.

##ACTIVIDADES DE OTROS
La gran diversidad de [actividades que se publican](/actividades-de-otros.md) produce un efecto de *infoxicación* y encontramos muchas actividades con poco interés STEM. No obstante si ves algo interesante, puedes ayudarnos y publicarlo [en el muro](/muro.md).

##Lo que sí que nos gusta
* Ocupa poco
* Buen diseño
* Es muy resistente a golpes.
