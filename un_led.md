# 2 Circuitos sencillos.


# Un LED

## CIRCUITO

Para las siguientes propuestas, el montaje es colocar un diodo LED, en este caso no es necesario complicarse, podemos montarlo diréctamente en el Arduino uno colocando el ánodo (pata más larga) en el pin13 y el cátodo (pata más corta) en masa GND, elegimos el pin 13 por estar al lado de GND

![](https://catedu.github.io/programa-arduino-mediante-codigo/img/Captura_de_pantalla_2015-05-19_a_las_11.31.53.png)

![](/assets/unled.png)

>No es una buena práctica conectar un diodo diréctamente sin pasar por una resistencia, pues en teoría es un cortocircuito, PERO si se hace no pasa nada pues Arduino tiene una limitación interna de 20mA

Luego lo recomendable es hacerlo pasar por una resistencia, usanto la placa PROTOBOARD

![](/assets/conexionLED.png)

Para el cálculo de la resistencia, debemos de tener en cuenta que la máxima corriente es 20mA, que la tensión de salida es 5V y que el diodo tiene una tensión Vd de funcionamiento, que depende de su color:

Rminima = (5V-Vd)/20mA

| Color | Vd | Resistencia mínima Ohm |
|-------|----|------------------------|
| Rojo | 1.8V | 160 |
| Amarillo | 3.2V | 140 |
| Verde | 3.2V | 90 |
