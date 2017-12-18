# Condensador

## Propuesta

Realizar un programa que cargue y descargue el condensador y que lo visualice en un objeto.

La propuesta es con un condensador de 10μF y dos resistencias de centenares de k, según[ lo visto en el módulo M1 ](https://catedu.gitbooks.io/ensena-pensamiento-computacional-con-arduino/content/condensador.html)esto nos dará un tiempo de carga y descarga de varios segundos

OJO CONECTAR EL PIN (-) DEL CONDENSADOR A GND

Las resistencias colocarlos de tal manera que uno sea para la carga y otro para la descarga

Un cable suelto, en uno extremo el terminal (+) del condensador y el otro suelto preparado para tocar la resistencia de carga o la de descarga.

Esta misma conexión que lo lea Arduino, por ejemplo por A0



 <img src="img/cto-condensador.png" width="435" height="510" />C

Visualizar la carga en un objeto Scratch que aumente de volumen:

{% youtube %}https://www.youtube.com/watch?v=08FM_y8rujc{% endyoutube %}

%accordion%Solución%accordion%

Es muy sencillo, fija el tamaño de la pelota al valor del pin A0

Lo hemos hecho a través de una variable auxiliar "carga" para poder visualizar numéricamente su valor.

<img src="img/condensador.png" width="336" height="149" />

El programa te lo puedes [descargar aquí](http://aularagon.catedu.es/materialesaularagon2013/arduino/M2/condensador.sb2).


%/accordion%

NOTA: Se puede aprovechar esta experiencia para:

- Calcular el tiempo de carga, si coincide con la fórmula T = 5RC
- Visualizar que la pelota se carga o aumenta de volumen muy rápidamente al principio y luego lentamente, tal y como indica[ la teoría vista en el módulo 1](https://catedu.gitbooks.io/ensena-pensamiento-computacional-con-arduino/content/condensador.html)
- Igualmente en la descarga


%/accordion%


