# Laboratorio-9

1.- Objetivo General
 
   - Analizar los amplificadores operacionales en circuitos mediante un osciloscopio y la ayuda de simuladores.

  1.1.- Objetivos Específicos
 
   - Identificar el comportamiento de los amplificadores operaciones con capacitores y con resistencias.
   
   - Analizar como se comportan los amplificadores operacionales con diferentes fuentes de voltaje a distintas frecuencias.
    
   - Identificar los datos tanto de entrada como de salida en el osciloscopio.

 2.- Marco Teórico

![image](https://user-images.githubusercontent.com/76134214/113245142-ef65f000-927b-11eb-951f-da6d10b0d1f5.png)

 3.- Lista de componentes
 
![image](https://user-images.githubusercontent.com/76132461/113213418-c9215f80-923d-11eb-9392-6006ad30ddd9.png)

 4.- DIAGRAMAS

Primer Circuito con osciloscopio

![image](https://user-images.githubusercontent.com/76132461/113228419-74401200-925a-11eb-940b-d64785f52353.png)

Segundo Circuito con osciloscopio

![image](https://user-images.githubusercontent.com/76132461/113228366-5377bc80-925a-11eb-84aa-178e8da95bee.png)

Tercer Circuito con osciloscopio

![image](https://user-images.githubusercontent.com/76132461/113228492-9e91cf80-925a-11eb-9eb1-396fada6ab85.png)

 5.- EXPLICACIÓN
    
 5.1.- PROCEDIMIENTO

 1. Se ingresa a la página multisim live, se crea una cuenta y se extraen de la biblioteca los materiales que vamos a utilizar.

2. Tanto las fuentes de voltaje como los las resistencias se configuran a los valores antes establecidos.

3. Al lado positivo de nuestra fuente de voltaje se coloca una resistencia de 1 Kohm, seguido se coloca una resistencia de 4.3 kohm y en ese punto entre la R1 y R2 se coloca nuestro amplificador.

4. Nuestro amplificador estará conectado a una segunda fuente de voltaje de 14 V y esta a su vez sera la que se conecta hacia el osciloscopio junto con nuestro otra fuente de 14 V.

5. El segundo circuito es similar al primero, lo que cambia es que se debe colocar un capacitor en lugar de la resistencia 2, este sera de 1 uF.

6. Para el tercer circuito se tendran 2 fuentes de voltaje y cada una se conectará con una fuente de voltaje de 300 y 200 ohms respectivamente.

7. Una de estas irá hacia otra resistencia de 1 kohm y el otro irá hacia una fuente de voltaje de 14 V.

8. De la otra salida del amplificador se conectará otra fuente de 14 V que servirá para medir con el osciloscopio.

6.- ANÁLISIS DE RESULTADOS

Analice y compare las formas de onda obtenidas en la práctica con los resultados obtenidos en el trabajo preparatorio. Comente dicha comparación.

Podemos observar que en el primer circuito en la onda de salida tenemos un voltaje pico de 4.28 V, en este circuito se ha trabajo solo con resistencias, la onda representa una onda senoidal representada en color verde. La onda morada es otra onda senoidal pero representa al voltaje de entrada que tenemos de la fuente de voltaje en este caso es de 998.98 V, acercandose a 1 V, tal y como se establecio en nuestra fuente. 

En el segundo circuito trabajamos con una fuente de voltaje de 5 V con una forma de onda pulsante, es debido a eso que el voltaje se mantiene estable en el punto maximo por milisegundos y de nuevo vuelve a ser cero. Al final del circuito podemos observar un valor de -14.089, se produce un voltaje negativo ya que al ser una onda pulsante nosotros estamos conectando en una fuente inversora, es por eso que nuestro voltaje es negativo.

En el tercer circuito se puede observar que el voltaje es de la onda de color morado es de 0.998 V acercandose a 1 V, es debido a que es el valor que nosotros establecimos en nuestras fuentes, pero solo se ve un color ya que esta una onda sobre la otra, debido a que tiene el mismo valor. Mientras que la onda amarilla tiene un voltaje pico de 8.28, si comparamos con la primera fuente podemos observar que es el doble de la primera, ya que utilizamos dos fuentes de voltaje de las mismas características entonces nuestro voltaje de salida se duplica.

7.- PREGUNTAS

1. Anote parámetros técnicos importantes de un amplificador operacional que deben ser tomados en cuenta al momento de utilizarlos en un proyecto.

* Ganancia de tensión en bucle abierto.

Es como en todo amplificador, el cociente entre la tensión de salida y la de entrada cuando hay realimentación. En los A.O. actuales se alcanzan valores de 100.000 o más y es frecuente que el fabricante los especifique en dB.

* Impedancia de entrada.

Normalmente expresa la parte resistiva vista desde los terminales de entrada. Son típicos los valores de algunos megaohmios.

* Impedancia de salida Zo.

Es asimismo la parte resistiva vista desde los terminales de salida. Son típicos valores entre 100 y 200 ohmios.

* Corriente de polarización de entrada (Input Bias Current).

Es la pequeña corriente que se deriva por los terminales de entrada. En general de del orden de algún microamperio.
Margen de tensiones de alimentación.Indican valores máximos y mínimos para un funcionamiento correcto del A.O. Vienen

* Margen de tensiones de entrada Vi.

La tensión en los terminales de entrada no debe superar nunca la de alimentación, pues en caso contrario podría dañarse el circuito.

* Margen de tensiones de salida.

Tal como hemos visto, la tensión máxima a la salida no puede ser superior a la de alimentación y cuando se alcanza esta tensión máxima de salida se dice que el A.O. está en saturación.

* Tensión diferencial de descentrado a la salida (off-set).

En un A.O. ideal la tensión de salida es nula cuando ambas entradas se hallan a potencial cero. En la práctica no encontramos con que esto no se cumple, y aparecen en los circuitos internos de entrada pequeñas tensiones que, una vez amplificadas por la alta ganancia del dispositivo pueden llevar a la salida incluso hasta el estado de saturación. Para evitar este inconveniente la mayoría de A.O. poseen métodos externos de corrección, que será conveniente emplear en circuitos en los que se requiera alta precisión (por ejemplo en seguidores de tensión).

* Relación de rechazo en modo común CMRR (Common mode rejection ratio).

En un A.O. ideal la salida es proporcional a la diferencia entre las señales de entrada, siendo ésta nula cuando el valor de ambas entradas es igual. En un A.O. real esto no se cumple exactamente, y entre dos pares de tensiones que mantengan la misma diferencia, la salida puede ser algo mayor en el caso de tensiones superiores. La CMRR es el cociente entre la amplificación diferencial y la de modo común; y cuanto mayor sea, más se acercará al caso ideal.

* Frecuencia de transición.

A esta frecuencia la ganancia en ciclo abierto del A.O. se reduce a la unidad.

* Velocidad de subida (stew-rate).

Es la velocidad de variación a la salida, y son valores típicos de 1V/ms a 10V/ms. Su principal afecto es limitar el ancho de banda de señales grandes.

2. Investigue las características de amplificadores operacionales distintos a los utilizados en esta práctica.

LM358

•	Amplio rango de suministro

o	Fuente única: 3 V a 32 V

o	Fuentes duales: ±1.5 V a ±16V

•	Drenaje de corriente de suministro baja independiente del voltaje de suministro: 0.7 mA típica

•	Ancho de banda de ganancia de unidad: 0.7 MHz

•	El rango de voltaje de modo común de entrada incluye tierra, lo que permite detección directa cerca de tierra.

•	Rango de voltaje de entrada diferencial igual al voltaje de alimentación de rango máximo: 32 V

•	Ganancia de voltaje diferencial de lazo abierto: 100 dB típica

•	Compensación de frecuencia interna

•	Parámetros de desviación y de polarización de entrada bajos

o	Bajo voltaje de desviación de entrada: 3 mV típica

	Versiones A: 2 mV típica

o	Corriente de desviación de entrada: 2 nA típ.

o	Corriente de polarización de entrada: 20 nA

	Versiones A: típico 15 nA típica

•	En los productos conformes a MIL-PRF-38535, todos los parámetros son probados a menos que se indique lo contrario. En todos los otros productos, el proceso de producción no necesariamente incluye la prueba de todos los parámetros.


LM324

• Rango de voltaje de operación: 3V a 32VDC. (Fuente sencilla)

• Rango de voltaje de operación: ±1.5V a ±16VDC. (Fuente dual)

• Bajo Voltaje Offset de entrada: 2 mV.

• Ancho de banda: 1 MHz

• Encapsulado: DIP14.

• Rango de temperatura de operación: 0°C hasta 70°C

• Multímetros digitales.

• Control de motores.

• Interfaces transductoras.

• Sistemas de adquisición de datos.

• Procesos de control industrial.

• Televisores y Home Theaters.

3. Investigue otras aplicaciones con circuitos más complejos que utilizan amplificadores operacionales.

Con la llegada de los amplificadores operacionales fue inevitable la mejora continua de los mismos los cuales han tenido un rediseño para mejorar, optimizar y añadir ciertas características. Se diseñaron circuitos integrados de función en especial, en los que hay mas de un amplificador operacional, para un fin en específico y funciones complejas.

Cada amplificador operacional cuenta con una hoja de datos conocido como Datasheet, para consultarlo y darse cuenta de la gran variedad de funciones y características técnicas. Algunos ejemplos donde se utilizan y se especializan son:

* Instrumentación y control automotrices.

* Circuitos integrados para comunicaciones.

* Circuitos integrados para radio, audio y video.

* Circuitos integrados para electrómetros usados en circuitos con impedancia de entrada muy elevada.

* Circuitos integrados que funcionen con una sola fuente de alimentación.

* Circuitos integrados que funcionen con fuentes de alimentación bipolares.

8.- CONCLUSIONES

* El comportamiento del amplificador operacional con resistencias y capacitores, se diferencia ya que el capacitor tendrá un valor fijo gracias a su fuente de voltaje y a su comportamiento ya que ira de 0 hasta el valor designado en la fuente en ciclos de encendido y apagado. Por el lado contrario la resistencia disminuirá la amplificación y demostrará una onda sinusoidal dependiendo de la variación de la fuente.

* Las diferentes fuentes de voltaje cambiaran la forma de la onda en el osciloscopio, como por ejemplo cuadradas y onduladas.

9.- BIBLIOGRAFÍA

Floyd, T.L. (2007). Principios de circuitos eléctricos (Octava ed.)

Amplificador operacional ideal. (s. f.). Electronicafacil. Recuperado 31 de marzo de 2021, de https://www.electronicafacil.net/tutoriales/Amplificador-operacional-ideal.html

Amplificadores operacionales duales LM358 - TI | DigiKey. (s. f.). Digikey. Recuperado 31 de marzo de 2021, de https://www.digikey.com.mx/es/product-highlight/t/texas-instruments/lm358-dual-operational-amplifiers

Amplificador Operacional LM324. (s. f.). Electronicalplugandplay. Recuperado 31 de marzo de 2021, de https://www.electronicaplugandplay.com/circuitos-integrados/product/480-amplificador-operacional-lm324
