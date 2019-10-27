#5 Mi primer programa

###Objetivo
Un programa sencillo que si giro el Sphero Mini diga un mensaje

##Programa
Cogeremos el evento GiroMax y le añadimos el audio con un mensaje

El programa lo puedes encontrar en este enlace

https://edu.sphero.com/remixes/5451216

![](/assets/2019-10-19 21_00_40-Window.jpg)

##Resultado

{% youtube %}https://youtu.be/xfpNphAzxDo{%endyoutube %}

##¿ Problemas ?

Puede ser que tu Sphero-mini no llegue al giro máximo, no no quieres que haya que ser tan bruto para que salte el mensaje

En Sensor Data puedes ver qué cantidad de giro ha hecho

![](https://catedu.gitbooks.io/sphero-mini/content/assets/2019-10-20%2013_37_13-Window.jpg)

si queremos que salte ya en el primer caso, sin necesidad de llegar al máximo:

![](/assets/2019-10-27 08_00_23-Window.jpg)

Simplemente bajamos la sensibilidad con otro tipo de programa, sin utilizar el evento giro máximo. En la ilustración el programa modificado para una sensibilidad de 100:

![](/assets/2019-10-27 08_02_36-Window.jpg)