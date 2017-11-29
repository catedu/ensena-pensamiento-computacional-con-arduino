
# Esto esta mal

## Directo: Esto esta mal

<img src="http://www.luisllamas.es/wp-content/uploads/2014/09/arduino-pulsador-1.png" width="400" height="248" />

La sencilla razón es la siguiente ¿cuando el interruptor o pulsador esté abierto qué tensión tendrá "Pin digital"?

En vista de protoboard sería así:

<img src="img/estomal.png" width="496" height="379" />

El primer pulsador cuando se cierra si que proporciona 5V al pin 12 por el cable azul pero... ¿y cuando no está pulsado?

El segundo pulsador cuando se cierra sí que proporciona 0V al pin 13 por el pin verde pero... ¿y cuando no está pulsado?



Ah!! y por supuesto ni se te ocurra esto, provocarías un cortocircuito:

<img src="http://www.luisllamas.es/wp-content/uploads/2014/09/arduino-pulsador-2.png" width="600" height="372" />

