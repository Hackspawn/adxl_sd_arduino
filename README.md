# Ejemplo de Uso de Arduino con Sparkfun ADXL345 y Escritura en tarjeta MicroSD

![alt text](https://github.com/Hackspawn/adxl_sd_arduino/blob/main/sketch_ADXL+MicroSD.jpg?raw=true)

### Según este esquemático de conexión

Se debe considerar el uso de las librerias Sparkfun ADXL345 y SD.

El orden de conexión del lector MicroSD es el siguiente:

| Arduino | Módulo MicroSD |
| ------------- | ------------- |
| GND  | GND  |
| 5V  | VCC  |
| D11  | MISO  |
| D12  | MOSI  |
| D13  | SCK  |
| D9  | CS  |

La conexión del ADXL345 es conexión I2C basado en la [guía de iniciación de Sparkfun](https://learn.sparkfun.com/tutorials/adxl345-hookup-guide/all)

