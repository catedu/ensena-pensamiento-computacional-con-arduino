
# LDR

LDR= Light Depended Resistor es una resistencia que disminuye su valor cuando aumenta la luz.

Si se coloca en serie con una resistencia de un valor parecido, el punto de unión (cable verde) tiene una tensión variable con la luz que lo puede leer Arduino, en este esquema lo lee por la entrada A0

<img src="img/img/ldresquema.png" width="476" height="449" />

Si hay luz, el LDR disminuye su resistencia por lo tanto disminuye el valor de la tensión en A0, y viceversa.




# LDR

## Propuesta

Realizar un programa que visualice en un objeto Scratch la cantidad de luz

El circuito es el siguiente: el LDR conectado a A0 y a una resistencia (la resistencia PULL UP para que la tensión que mida A0 sea la del LDR) y un objeto que aumente de tamaño según el valor de A0

<img src="img/img/cto-ldr.png" width="471" height="493" />

Y el vídeo

<iframe width="425" height="350" src="//www.youtube.com/embed/b89sS6mQ4_Q" frameborder="0"></iframe>

<script type="text/javascript">var feedback16_93text = "Solución";</script><input type="button" name="toggle-feedback-16_93" value="Solución" class="feedbackbutton" onclick="$exe.toggleFeedback(this,false);return false" />

### Retroalimentación

El programa es el siguiente:

<img src="img/img/ldr.png" width="344" height="162" />

OOOPAAAA !!! ¡¡ Pero si es el mismo que el que acabamos de ver !!! [El condensador](condensador.html)

Simplemente se ha cambiado el nombre de la variable, allí se llamaba **carga** y aquí **oscuridad** ¡¡¡ vaya tontería !!!

