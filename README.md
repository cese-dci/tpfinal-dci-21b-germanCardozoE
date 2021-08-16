## Trabajo práctico final de la asignatura DCI ##
Este repositorio contiene el trabajo práctico final para la asignatura de Diseño de Circuitos Impresos de la carrera de posgrado de FIUBA.

* Autor: Cardozo Germán Eloy
* Título corto del trabajo:  ESP32-CAM
* Descripción:  El siguiente proyecto incluye tanto el circuito esquemático como el diseño del PCB realizado en kicad. A su vez se anexan diversas hojas de datos y bibliotecas utilizadas en su desarrollo.
ESP32-CAM es un módulo WiFi y Bluetooth que integra una pequeña cámara por lo que puede funcionar de manera independiente.
La camara OV2640 de 2MP integra un sensor de imagen CMOS UXGA (1632*1232) de 1/4 de pulgada. El pequeño tamaño del sensor y el bajo voltaje de operación brindan todas las características de una sola cámara UXGA y un procesador de imágenes. A través del control de bus SCCB, puede generar datos de imagen de 8/10 bits de varias resoluciones, como fotograma completo, submuestreo, zoom y ventanas.
La imagen UXGA de esta camara puede alcanzar hasta 15 cuadros por segundo (hasta 30 cuadros para SVGA y 60 cuadros para CIF). Los usuarios tienen un control completo sobre la calidad de la imagen, el formato de datos y la transmisión.
Todas las funciones de procesamiento de imágenes, incluida la curva gamma, el balance de blancos, el contraste, el croma, etc. se pueden programar a través de la interfaz SCCB.
Los sensores de imagen Omni Vision utilizan una tecnología de sensor única para mejorar la calidad de la imagen y reducir las imágenes en color nítidas y estables mediante la reducción o eliminación de defectos ópticos o electrónicos, como el ruido de patrón fijo, manchas y flotación.

## Principales Características ##
• Modelo: ESP32-CAM + Cámara OV2640
• Voltaje de Alimentación ESP 32 CAM: 5V
• Módulo Wi-Fi BT 802.11b/g/n
• Tipo de cámara: OV2640 2MP
• El modulo ESP 32CAM tiene CPU 32 bits de doble núcleo de baja potencia
• Frecuencia principal de hasta 240 MHz
• Potencia informática de hasta 600 DMIPS
• Velocidad de reloj de hasta 160 MHz
• Incorpora SRAM 520Kb, 4MPSRAM externa
• El modulo ESP-32 CAM Soporta interfaces: UART / SPI / I2C / PWM / ADC / DAC
• El modulo ESP-32-CAM Soporta cámaras OV2640 y OV7670, Flash Incorporado
• El modulo ESP 32-CAM Soporta tarjetas TF micro SD (Máximo 4 GB)
• El modulo ESP-32CAM Soporta la carga de imagen WiFi
• Compatible con modos de operación STA / AP / STA+AP
• Con antena PCB
• El modulo ESP32CAM integra conectores u.FL y FPC


## Licencia de este trabajo ##
Licencia GNU GPL

## Estructura del TP FINAL ##

Se propone y se pide utilizar la siguiente estructura.

* doc: Toda la información sobre el circuito, principalmente de autoría o procesamiento propio. Por ejemplo:
  * Notas de ingeniería propias.
  * Notas de aplicación propias.
  * Estudios previos, estado del arte, resumen de las investigaciones.
  * Notas con cálculos.
  * Dibujos adicionales.
  * Fotos de los prototipos.
  * Presupuestos, cotizaciones.
* info: Toda la iformación recolectada, principalmente de terceros, como por ejemplo:
  * Hojas de datos.
  * Notas de aplicación.
  * Info de productos comerciales.
  * Info en internet.
* pcb: Archivos de diseño esquemático y pcb.
