
# Esto esta mal

## Directo: Esto esta mal

![](/assets/arduino-pulsador-1.png)

_Fuente Luis Llamas https://www.luisllamas.es/leer-un-pulsador-con-arduino/_

La sencilla razón es la siguiente ¿cuando el interruptor o pulsador esté abierto qué tensión tendrá "Pin digital"?

En vista de protoboard sería así:

<img src="img/estomal.png" width="496" height="379" />

El primer pulsador cuando se cierra si que proporciona 5V al pin 12 por el cable azul pero... ¿y cuando no está pulsado?

El segundo pulsador cuando se cierra sí que proporciona 0V al pin 13 por el pin verde pero... ¿y cuando no está pulsado?


Ah!! y por supuesto ni se te ocurra esto, provocarías un cortocircuito:

![](assets/arduino-pulsador-2.png)

_Fuente Luis Llamas https://www.luisllamas.es/leer-un-pulsador-con-arduino/_

Bueno resumiendo: lo que tienes que hacer es una de estas dos configuraciones, la opción recomendada es PULL UP para que OFF = 0 y ON = 1

![](assets/arduino-pulsador-3.png)

_Fuente Luis Llamas https://www.luisllamas.es/leer-un-pulsador-con-arduino/_
