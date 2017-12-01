
# 3 Circuitos más complejos

# LDR y LEDs

## Propuesta

Esta vez vamos a convertir el valor de la oscuridad en luces. Para ello necesitaremos:

- **10 LEDs** puestos consecutivamente. Vamos a colocarlos desde el pin 2 hasta el 11 (el 1 está ocupado con TX)
- El sensor LDR conectado a una entrada A0
- El programa tiene que convertir el valor de la oscuridad que detecta el LDR en las luces, es decir cuanto más oscuridad más luces encendidas.

<img src="img/cto-ldr-luces2.png" width="775" height="520" />

{% youtube %}https://www.youtube.com/watch?v=78hqYoimEV4{% endyoutube %}

%accordion%Solución%accordion%

La solución tiene la complejidad del valor de la entrada A0 que va desde 0 hasta 1023 por lo tanto, hay que convertir estos valores en valores del 2 al 11 correspondiente a los LEDs

La forma más sencilla de reconvertir A0 es dividir A0 entre 100 y sumarle un 1 de esta manera aproximadamente los valores se convierten en 2-11

Si el LED se menor que el valor A0 ya convertido, encender el LED, en caso contrario apagarlo

<img src="img/ldr-leds.png" width="399" height="348" />

El programa te lo puedes [descargar aquí](http://aularagon.catedu.es/materialesaularagon2013/arduino/M3/ldr-luces.sb2)


%/accordion%

