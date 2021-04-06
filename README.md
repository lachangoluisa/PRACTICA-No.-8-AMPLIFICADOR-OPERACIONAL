# PRACTICA-No.-8-AMPLIFICADOR-OPERACIONAL
INFORME

OBJETIVO GENERAL 

 * Verificar el principio de funcionamiento de un amplificador operacional.

OBJETIVOS ESPECIFICOS

 * Analizar algunas aplicaciones basicas con el amplificador operacional.
 * Familiarizarse con el uso de instrumentos de medida.

MARCO TEÓRICO

![MENTEFACTO LAB9](https://user-images.githubusercontent.com/76057459/113743623-7de9cf80-96c9-11eb-9f64-f0f9933c0bd9.png)

FIG1.AMPLIFICADOR OPERACIONAL IDEAL

![amplificador operacional ideal](https://user-images.githubusercontent.com/76057459/113602697-88906000-9608-11eb-8846-88fa0a06337b.png)
FIG2.AMPLIFICADOR OPERACIONAL

![amp op graf](https://user-images.githubusercontent.com/76057459/113743889-c7d2b580-96c9-11eb-80f5-d43171ca0a50.png)


DIAGRAMAS

![WhatsApp Image 2021-04-05 at 12 38 46 PM](https://user-images.githubusercontent.com/76057459/113657326-57914900-9663-11eb-8bf5-b1bdc35171a6.jpeg)



LISTA DE COMPONENTES

* Generador de señales
* Fuente DC
* Osciloscopio.
* Protoboard
* Multimetro
* Cables conductores
* Resistencias , capacitores
* Amplificadores Operacionales



EXPLICACIÓN
1.- Construya en el protoboard cada uno de los circuitos de la figura 1. Muestre simultáneamente las señales de entrada y salida en un osciloscopio. Capture las formas de onda.

2.- Determine y analice la relación entre las señales de entrada y salida en cada uno de lOS circuitos indicados en la figura 1.


3.- En todos los casos emplee un amplificados LM741.


7.- DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN


8.- ANALISIS DE RESULTADOS 

1.- Analice y compare las formas de onda obtenidas en la práctica con los resultados obtenidos
en el trabajo preparatorio. Comente dicha comparación.

CIRCUITO 1

![WhatsApp Image 2021-04-06 at 11 35 08 AM](https://user-images.githubusercontent.com/76057459/113748438-1d10c600-96ce-11eb-933d-517d29f4d118.jpeg)


![WhatsApp Image 2021-04-06 at 11 34 23 AM](https://user-images.githubusercontent.com/76057459/113748348-fd799d80-96cd-11eb-8bd1-7d343b96ae33.jpeg)


 ANALISIS CIRCUITO 1
 La onda de entrada y salida son senoidales 
 En este circuito se uso un aplificador operacional inversor 
 
 CIRCUITO 2
 
 ![WhatsApp Image 2021-04-06 at 12 38 15 PM](https://user-images.githubusercontent.com/76057459/113755190-a8418a00-96d5-11eb-8b2f-f295e1fbffb4.jpeg)

 ANALISIS CIRCUITO 2
 
 La onde de entrada y salida presentan una inclinacion es decir se presenta como una onda triangular  debido a los capacitores 
 En el circuito esta empkeado un amplificador operacional integrador inversor y se puede ver una onda cuadrada con desfase 
 
 CIRCUITO 3
 
 ![WhatsApp Image 2021-04-06 at 11 35 45 AM](https://user-images.githubusercontent.com/76057459/113748537-374aa400-96ce-11eb-9538-c912a958a260.jpeg)

 ![WhatsApp Image 2021-04-06 at 11 37 28 AM](https://user-images.githubusercontent.com/76057459/113748560-3fa2df00-96ce-11eb-8533-840fb935196d.jpeg)

 
 ANALISIS DE CIRCUITO 3
 
 La onda de entrada y salida son senoidales 
 En este circuito esta implementado un amplificador operacional sumador  inversor el cual añade algebraicamente las señales y sumarlas 
 

9.- PREGUNTAS

1. Anote parámetros técnicos importantes de un amplificador operacional que deben ser
tomados en cuenta al momento de utilizarlos en un proyecto.

Parámetros de los amplificadores operacionales

Impedancia de entrada :
Es la resistencia entre las entradas del amplificador.

Impedancia de salida :
Es la resistencia que se observa a la salida del amplificador.

Ganancia en lazo abierto : 
Indica la ganancia de tensión en ausencia de realimentación. Se puede expresar en unidades naturales (V/V, V/mV) o logarítmicas (dB). Son valores habituales de 100.000 a 1.000.000 V/V. Algunos fabricantes denominan a este parámetro Large-signal differential voltage amplification (Amplificación de tensión diferencial para gran señal).

Tensión en modo común :
Es el valor promedio de tensión aplicada a ambas entradas del amplificador operacional.

Tensión de desequilibrio (offset) de entrada:
Es la diferencia de tensión, entre las entradas de un amplificador operacional que hace que su salida sea cero voltios.
 
Corriente de desequilibrio de entrada:
Es la diferencia de corriente entre las dos entradas del amplificador operacional, que hace que su salida tome el valor cero.

Tensión de entrada diferencial :
Es la mayor diferencia de tensión entre las entradas del operacional que mantienen el dispositivo dentro de las especificaciones.

Corriente de polarización de entrada : 
Corriente media que circula por las entradas del operacional en ausencia de señal.

Rapidez de variación de tensión (slew rate, en idioma inglés):
Es la máxima variación de la tensión de salida respecto de la variación del tiempo, como respuesta a un tensión de escalón. Se mide en V/μs, kV/μs o unidades similares. Este parámetro está limitado por la compensación en frecuencia de la mayoría de los amplificadores operacionales.

Relación de Rechazo en Modo Común (RRMC, o CMRR en sus siglas en inglés): 
Es la capacidad de un amplificador de rechazar señales en modo común.


2. Investigue las características de amplificadores operacionales distintos a los utilizados en esta practica.

Amplificador Operacional No Inversor 

 Este circuito es muy parecido al inversor, la diferencia es que la señal se introduce por el terminal no inversor, lo cual va a significar que la señal de salida estará en fase con laseñal de entrada y amplificada. El análisis matemático será igual que en el montaje inversor.  la ganancia de éste amplificador no puede ser menor que 1. la corriente de entrada al operacional es cero, por lo tanto I1 es igual a I2.  tiene una ganancia en tensión Av = 1 + R1 / R2 . Esto quiere decir que la salida será Av veces la entrada, sin invertirse la señal ya que Av es positiva. 

Amplificador Operacional Diferencial 

 Este dispositivo nos permite obtener la derivada de la señal de entrada. En el caso general la tensión de entrada variará con el tiempo Vi= Vi(t). La principal diferencia que se observa en este circuito es la presencia de un condensador de capacidad constante C. Como se sabe la carga Q que almacena un condensador es proporcional a su capacidad C y a la diferencia de potencial V a la que estén sometidos las armaduras de éste (Q=CV). Es fácil entender que si la tensión varía con el tiempo y la capacidad del condensador es constante, la carga que éste almacena también variará con el tiempo, Q= Q(t) 

Amplificador Sumador No inversor 

Tiene múltiples entradas en el pin no inversor. Al igual que en un sumador inversor cada entrada tiene su propia impedancia de entrada que esta por el orden de 100 Mega Ohmios o más y solo hay una impedancia de salida que esta por el orden de mili Ohmios o menos. 

Amplificador Operacional Seguidor de Voltaje 

 Este amplificador hace que la salida siga a la entrada, es decir el voltaje de salida es el mismo voltaje de entrada. Al presentar una alta impedancia de entrada (por el orden de Megas de Ohm o más), se garantiza una baja potencia de entrada, que a su vez garantiza que la señal de entrada no se distorsionara al conectarse al pin no inversor, y además que la señal de entrada quedara en su totalidad en la impedancia de entrada. Al presentar una muy baja impedancia de salida (por el orden de milis de Ohm) se garantiza que haya una transferencia total de potencia a la RL de salida. Por esta razón al Opamp seguidor también se le conoce como buffer y se usa para acoplar impedancias. 


3. Investigue otras aplicaciones con circuitos más complejos que utilizan amplificadores operacionales.

Ejemplo de amplificador operacional
![ejemp'lo ](https://user-images.githubusercontent.com/76057459/113758435-7a5e4480-96d9-11eb-9d55-233f6cfa6963.jpeg)


* Interruptor Crepuscular con Amplificador Operacional
![WhatsApp Image 2021-04-06 at 12 25 52 PM](https://user-images.githubusercontent.com/76057459/113753026-3e27e580-96d3-11eb-8c40-f2fc389e35f9.jpeg)

* Distorsionador Fuzz para Guitarra (circuito)

![WhatsApp Image 2021-04-06 at 12 26 14 PM (2)](https://user-images.githubusercontent.com/76057459/113753434-b1c9f280-96d3-11eb-955e-bffccb2232b4.jpeg)


* Alarma por exceso de temperatura

![WhatsApp Image 2021-04-06 at 12 27 26 PM](https://user-images.githubusercontent.com/76057459/113753337-9c54c880-96d3-11eb-8831-926941b6a87a.jpeg)


* Probador de continuidad con 741

![Uploading WhatsApp Image 2021-04-06 at 12.27.37 PM.jpeg…]()



10.-CONCLUSIONES

Un amplificador se le da la configuracion de inversor cuando  la señal de  salida es negativa y de entrada es positiva

Cuando se implementa un amplificador operacional actua de acuerdo a los elementos conectados al circuito o de la onda de entrada

en el circuito 1 y 2 se observa ondas senoidales en las que se uso un aplificador operacional que aumento la señal de entrada

en el circuito 2 se observa que la señal tiene forma de diente de sierra  por el capacitor



11.- BIBLIOGRAFIAS


https://www.diarioelectronicohoy.com/blog/el-amplificador-operacional

https://latecnicalf.com.ar/descargas/material/electronicaanalogica/Repaso%20resumen%20Amplificadores%20Operacionales.pdf

https://hetpro-store.com/TUTORIALES/amplificador-operacional/

https://unicrom.com/circuitos/circuitos-con-amplificadores-operacionales/

http://www.academicos.ccadet.unam.mx/jorge.marquez/cursos/Instrumentacion/AmplificadoresOperacionales.pdf


12.- ANEXOS
