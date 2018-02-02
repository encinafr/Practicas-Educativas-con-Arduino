# Salidas digitales

En este capítulo aprenderás a programar diferentes prácticas utilizando las salidas digitales de la placa de arduino. Para cada una se explica la parte de electrónica que deberás conocer antes de programarlas. Observarás además que puedes programarlas utilizando los lenguajes de programación por bloques o textual de Arduino.


---


<br><br>


## ¿Qué es una señal digital?

Una señal digital es aquella que sólo puede tomar ciertos valores (alto o bajo). Su forma característica es conocida como señal de onda cuadrada y las representaciones se realizan en el dominio del tiempo. La función principal de las salidas digitales es entregar una señal de control que le dará funcionalidad a un circuito electrónico que será el encargado de cumplir con las funciones que el usuario requiera.

![Señal digital](assets/senal-digital.png)


<br>


## Salidas digitales en Arduino

En arduino disponemos de 14 pines digitales serigrafiados con los números del 0 al 13. Estos pines son utilizados en modo digital para entradas y salidas, incluso algunos de ellos, serigrafiados con el símbolo de alterna (~), pueden ser también utilizados como pines de salida analógica en modo PWM.

La salida digital toma los valores 0V (bajo) ó 5V (alto).

![Salidas digitales en Arduino](assets/salidas-digitales.png)

Los pines de salida han sido diseñados para entregar señales de voltaje, no para suplir corriente a un circuito. El máximo de corriente que puede entregar un pin de salida es de aproximadamente 40mA (suficiente para encender un LED). Las cargas que vamos a manejar no deben superar los 5V ni consumir más de 40mA.


---


<img src="http://i.creativecommons.org/l/by-sa/4.0/88x31.png" /><br>
Esta obra está bajo una licencia de [Creative Commons Reconocimiento-CompartirIgual 4.0 Internacional](https://creativecommons.org/licenses/by-sa/4.0/deed.es_ES).

2018 [Asociación Programo Ergo Sum](https://www.programoergosum.com)