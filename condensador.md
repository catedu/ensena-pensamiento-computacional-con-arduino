
# Condensador

## ¿Qué es?

Es un elemento que consta de dos placas separadas que son capaces de cargarse eléctricamente, su capacidad se mide en Faradios. Se puede interpretar como un globo que nos permite hincharlo de aire, y la capacidad los litros.

**ATENCIÓN** Los condensadores (a partir de μF son electrólíticos) tienen** POLARIDAD QUE ES IMPORTANTE RESPETARLA,** es decir, tienen un pin marcado con el signo (-) normalmente con franja blanca que tiene que ir al (-) o masa (GND 0V) de lo contario, revientan, con el consecuente peligro, más peligrosos cuanto más capacidad tienen.

**ATENCIÓN** Los condensadores tienen una tensión máxima de trabajo, marcado en el propio condensador, en nuestro caso los condensadores marcan 25V, luego se pueden utilizar sin problemas con el Arduino que la tensión máxima es 5V. Como si fuera la máxima presión que aguanta el globo antes de explotar.



## Carga y descarga

Si lo hacemos a través de una resistencia, tarda un tiempo a cargarse y también a descargarse (como si en el globo lo deshincháramos pero estrechando la boca)

El circuito de carga sería

<img src="img/img/carga.png" width="188" height="404" /><img src="ctocarga.png" width="188" height="386" />

fíjate que el lado (-) (la banda blanca) está conectado a GND

El circuito de descarga sería

<img src="img/img/descarga.png" width="199" height="367" /><img src="ctodescarga.png" width="160" height="356" />

## Cálculos

El tiempo de carga y de descarga se calcula con la fórmula :

T = 5 R C

En el caso de los circuitos de arriba T = 5 * 100k * 10μ = 5 * 100 000 * 0.00001 = 5 segundos

Igual que un globo, la carga evoluciona muy rápidamente al principio, pero a medida de que se va llenando, cuesta más, la gráfica de carga de un condensador es la siguiente:

<img src="http://e-ducativa.catedu.es/44700165/aula/archivos/repositorio//2750/2951/html/img13.JPG" width="351" height="229" />

Y para la descarga es la siguiente

<img src="http://e-ducativa.catedu.es/44700165/aula/archivos/repositorio//2750/2951/html/img15.JPG" width="342" height="232" />


# Condensador

## Propuesta

Realizar un programa que cargue y descargue el condensador y que lo visualice en un objeto.

La propuesta es con un condensador de 10μF y dos resistencias de centenares de k, según[ lo visto en el módulo M1 ](http://aularagon.catedu.es/materialesaularagon2013/arduino/M1/condensador.html)esto nos dará un tiempo de carga y descarga de varios segundos

OJO CONECTAR EL PIN (-) DEL CONDENSADOR A GND

Las resistencias colocarlos de tal manera que uno sea para la carga y otro para la descarga

Un cable suelto, en uno extremo el terminal (+) del condensador y el otro suelto preparado para tocar la resistencia de carga o la de descarga.

- <img src="img/img/cto-condensador.png" width="435" height="510" />C

Visualizar la carga en un objeto Scratch que aumente de volumen:

<iframe width="425" height="350" src="//www.youtube.com/embed/08FM_y8rujc" frameborder="0"></iframe>

<script type="text/javascript">var feedback15_93text = "Solución";</script><input type="button" name="toggle-feedback-15_93" value="Solución" class="feedbackbutton" onclick="$exe.toggleFeedback(this,false);return false" />

### Retroalimentación

Es muy sencillo, fija el tamaño de la pelota al valor del pin A0

Lo hemos hecho a través de una variable auxiliar "carga" para poder visualizar numéricamente su valor.

<img src="img/img/condensador.png" width="336" height="149" />

El programa te lo puedes [descargar aquí](condensador.sb2) (sb2 - 15.35 <abbr lang="en" title="KiloBytes">KB</abbr>).

NOTA: Se puede aprovechar esta experiencia para:

- Calcular el tiempo de carga, si coincide con la fórmula T = 5RC
- Visualizar que la pelota se carga o aumenta de volumen muy rápidamente al principio y luego lentamente, tal y como indica[ la teoría vista en el módulo 1](http://aularagon.catedu.es/materialesaularagon2013/arduino/M1/condensador.html)
- Igualmente en la descarga

