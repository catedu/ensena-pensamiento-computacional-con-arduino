
# 1 Introducción

Arduino es una plataforma de electrónica abierta para la creación de prototipos basada en software y hardware flexibles y fáciles de usar. En este capítulo ofrecemos una guía de referencia rápida que siempre puede ser ampliada accediendo a la página oficial: [www.arduino.cc](/www.arduino.cc)
![](/assets/2017-12-18 12_43_39-Fundamentos de Arduino · Programa Arduino mediante código.png)
## ¿Qué es Arduino?
Arduino es una tarjeta electrónica que integra básicamente a un microcontrolador y un conjunto de pines de conexión de entradas y salidas que permiten, mediante un determinado programa, interaccionar con el medio físico mediante sensores y actuadores electrónicos. De esta forma podrás crear tus propios proyectos tecnológicos, dotarlos de sensores que detecten magnitudes físicas como luz, calor, fuerza, etc… y en base a esa información, escribiendo un programa, activar otros dispositivos (actuadores) como pequeñas bombillas, ledes, servomotores, pequeños motores DC, relés, etc… Los sensores se conectan a los pines de entrada y los actuadores a los de salida.
_¿Sabías que.... ? Uno de los co-creadores de Arduino es Español, de Zaragoza: David Cuartieles [+info](https://es.wikipedia.org/wiki/Arduino)_
## ¿Qué es un microcontrolador?
Es un circuito integrado que se puede programar, o sea que puede ejecutar las órdenes que tenga almacenadas en su memoria. Tiene las tres funciones principals de un computador: la unidad central de proceso, memoria y entradas y salidas.
Arduino utiliza la marca ATMEL, y el modelo de microcontrolador depende del tipo de tarjeta, por ejemplo la tarjeta Arduino Uno utiliza el micro ATMEL MEGA 328P.
## ¿Qué son las entradas y salidas?
Mediante los conectores de Arduino correspondientes a las entradas y salidas podemos comunicar nuestros programas con el “mundo exterior”. Si queremos leer el valor de la magnitud física medida por un sensor, por ejemplo una LDR que detecta el nivel de luminosidad, lo tendremos que hacer conectando el sensor a uno de los pines de entrada (en este caso analógicas) de la tarjeta.
De esta forma con una simple instrucción de lectura en el programa, podremos obtener el valor de la magnitud física. Si nuestra intención es actuar o “hacer algo” una vez leído el valor del sensor, por ejemplo encender un led si el sensor de luminosidad detecta oscuridad, tendremos que conectar el
actuador (en este caso el led) a un pin de salida que proporcionará la corriente necesaria para activarlo.
En Arduino las entradas pueden ser analógicas o digitales y las salidas sólo digitales. Cada pin digital tiene doble función entrada o salida. En la zona de configuración del programa hay que indicar explícitamente mediante una instrucción cuál es función desempeña un determinado pin.
## Más información por favor !!
No nos queremos extender más pero si necesitas la información anterior con más detalle y más posibilidades que no hemos mencionado, visita  los contenidos de nuestro curso [Programa Arduino mediante código](https://catedu.gitbooks.io/programa-arduino-mediante-codigo/content/index0.html) 

