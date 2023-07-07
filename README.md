# Raspberrypi-Arduino-Communication
For this project I was working with a Raspberry pi 4 and an Arduino Uno.

Raspberry pi communicates with the Arduino via Serial communication. This is enables by the UART(Universal Asynchronous Reception and Transmission) protocol. Both board work with multi-master protocol as the communication od mutual i.e. from both. Theres also a master-slaves protocol seen where the instructions come from on source e.g. connecting and arduino to other sensors and actuators.

For Serial communication, we can use the usb port or GPIO pins from both boards. Note that you cannot use both at any instance. You can connect to the Arduino with the printer cable the usual way and then connect the usb side of the cable to one of the usb ports on your Raspberry pi.