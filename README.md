# CONTROLADOR-TEMPERATURA-MAX31865-RELE-OLED




# Objetivos:

1.- Open Source.

2.- Control de temperatura de aceite por medio de un ESP32  .

3.- Varias entradas y dos relés: voltaje, %carga, etc.


# Contenido del repositorio:

PCB Datasheet Fotos

# Documentation:

Usa los siguientes componentes importantes:

MAX31865

![image](https://user-images.githubusercontent.com/40340747/225104840-7f288b6a-2d6b-44aa-809c-3c1a69e25dee.png)

(De Adafruit)
 
[MAX31865.pdf](https://github.com/SalgaCorp/CONTROLADOR-TEMPERATURA-MAX31865-RELE-OLED/files/10972528/MAX31865.pdf)

El módulo MAX31865 se puede configurar para trabajar con sensores PT100 de 2, 3 o 4 hilos. La configuración por defecto es para sensores de 4 hilos. 

El Módulo transmisor MAX31865 permite obtener de forma sencilla y confiable las mediciones de temperatura de los sensores RTD PT100. El módulo se encarga de realizar la lectura de resistencia del sensor PT100 y convertir esta señal analógica en un dato digital para ser interpretado por un microcontrolador. El chip MAX31865 posee un conversor ADC delta-sigma de precisión con una resolución de 15 bits, equivalente a 0.03125ºC. El protocolo de comunicación o interfaz es de tipo SPI.

El módulo está configurado por defecto para sensores PT100, por lo que el valor de Rref es de 430 Ohm. Para trabajar con sensores PT1000 debemos cambiar la resistencia de 430 Ohm por una de 4.3K Ohm.


# Enlaces y librerias:

https://github.com/adafruit/Adafruit_MAX31865

https://learn.adafruit.com/adafruit-max31865-rtd-pt100-amplifier?view=all



![image](https://user-images.githubusercontent.com/40340747/225102488-39eaa55c-a63a-45f5-bf0e-7ba1ecd27e59.png)


# Contact Us

Call or WhatsApp 

https://api.whatsapp.com/send?phone=56966814899
