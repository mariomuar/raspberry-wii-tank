# raspberry-wii-tank

# ENGLISH
# Raspberry Pi & Wiimote RC Tank

A personal robotics project where I designed and programmed the control system for a motorized toy tank. Powered by a Raspberry Pi as its central processing unit, the tank can be driven remotely in real-time using a Nintendo Wii remote (Wiimote).

## Built With
* **Python:** Core logic for hardware integration and motor control.
* **Raspberry Pi:** Central microcontroller.
* **Bluetooth:** Wireless communication protocol for the controller.

## Demo
*[Note: Add a GIF or a couple of photos showing the tank in action here]*

## How It Works
The main Python script handles the Bluetooth connection with the Wiimote to read user inputs continuously. When it detects button presses or accelerometer shifts, the script translates these signals into directional movement commands. These commands are then routed through the Raspberry Pi's GPIO pins to drive the tank's motors.

____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

# ESPAÑOL
# Tanque Controlado por Raspberry Pi y Mando de Wii

Este es un proyecto personal de robótica donde diseñé y programé el control de un tanque de juguete motorizado. Utiliza una Raspberry Pi como cerebro y permite el manejo remoto en tiempo real mediante un mando de la consola Nintendo Wii.

## Tecnologías utilizadas
* **Python:** Para toda la lógica de control e integración de hardware.
* **Raspberry Pi:** Como unidad central de procesamiento.
* **Bluetooth:** Para la comunicación con el mando de Wii.

## Demostración
*[Nota: Aquí te recomiendo subir un pequeño GIF o un par de fotos del tanque]*

## Cómo funciona
El script principal en Python se encarga de leer los inputs del mando de Wii mediante conexión Bluetooth. Al detectar la pulsación de los botones o el acelerómetro, el código traduce estas señales en comandos de movimiento que se envían a los motores del tanque a través de los pines GPIO de la Raspberry.
