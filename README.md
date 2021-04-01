# Laboratorio-9

1.- Objetivo General
 
   - Analizar los amplificadores operacionales en circuitos mediante un osciloscopio y la ayuda de simuladores.

  1.1.- Objetivos Específicos
 
   - Identificar el comportamiento de los amplificadores operaciones con capacitores y con resistencias.
   
   - Analizar como se comportan los amplificadores operacionales con diferentes fuentes de voltaje a distintas frecuencias.
    
   - Identificar los datos tanto de entrada como de salida en el osciloscopio.

 2.- Marco Teórico

 3.- Lista de componentes
 
![image](https://user-images.githubusercontent.com/76132461/113213418-c9215f80-923d-11eb-9392-6006ad30ddd9.png)

 4.- DIAGRAMAS

 5.- EXPLICACIÓN
    
 5.1.- PROCEDIMIENTO

 1. Se ingresa al programa Proteus y se extraen los materiales que vamos a utilizar de la biblioteca.

2. Tanto las fuentes de voltaje como los las resistencias se configuran a los valores antes establecidos.

3. Al lado positivo de nuestra fuente de voltaje se coloca una resistencia de 1 Kohm, seguido se coloca una resistencia de 4.3 kohm y en ese punto entre la R1 y R2 se coloca nuestro amplificador.

4. Nuestro amplificador estará conectado a una segunda fuente de voltaje de 14 V y esta a su vez sera la que se conecta hacia el osciloscopio junto con nuestro otra fuente de 14 V.

5. El segundo circuito es similar al primero, lo que cambia es que se debe colocar un capacitor en lugar de la resistencia 2, este sera de 1 uF.

6. Para el tercer circuito se tendran 2 fuentes de voltaje y cada una se conectará con una fuente de voltaje de 300 y 200 ohms respectivamente.

7. Una de estas irá hacia otra resistencia de 1 kohm y el otro irá hacia una fuente de voltaje de 14 V.

8. De la otra salida del amplificador se conectará otra fuente de 14 V que servirá para medir con el osciloscopio.

6.- ANÁLISIS DE RESULTADOS

Analice y compare las formas de onda obtenidas en la práctica con los resultados obtenidos
en el trabajo preparatorio. Comente dicha comparación.

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

8.- CONCLUSIONES

9.- BIBLIOGRAFÍA

Floyd, T.L. (2007). Principios de circuitos eléctricos (Octava ed.)
