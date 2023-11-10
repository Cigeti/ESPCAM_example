# ESPCAM_example

Proyecto ralizado para equipar a los estudiantes con conocimientos basicos para implementar y programar un ESPCAM para futuros proyectos.

## Paso 1: Instalacion de los paquetes para el ESP

- Abrir Arduino IDE
- Ir a la parte de archivos 
- Preferencias 
- En la parte de URL se pega el siguiente link: https://dl.espressif.com/dl/package_esp32_index.json
- Le damos aceptar 

## Paso 2: Descarga de la placa
- Herramientas
- Placa 
- Gestor de tarjetas 
- Buscar: esp32 
- Descargar la que dice: ESP32(by espressif Systems)

## Paso 3: Eleccion de la placa
- Herramientas 
- Placa
- ESP32 Arduino 
- Elegir la placa que dice: ESP Wrover Module

## Paso 4: Partition scheme
- Herramientas
- Partition scheme: Huge APP
## Contribución

Si deseas contribuir a este proyecto, por favor sigue las siguientes pautas de contribución.

## Problemas o Sugerencias

- Antes de subir la programacion debes desconectar la placa y conectar los pines IO0 con GND, despues conectas la placa y subes la programacion.
A la hora de ejecutar el programa desconectas esas conexiones.

## Conexiones del ESPCAM al Convertidor 
________________________________________________
    VCCIO del convertidor con los 5v del ESPCAM
________________________________________________
    TXD del convertidor con el U0R del ESPCAM
________________________________________________
    R0D del convertidor con el U0T del ESPCAM
________________________________________________
    GND del convertidor con el GND del ESPCAM
________________________________________________
