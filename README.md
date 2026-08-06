Goal of this project is to design a device that does something once ambient brightness becomes bright enough.

I will be keeping things as "simple", this is mostly for me to get practice coding drivers and writing programs for embedded systems. 
Trying to interface with the common communications and in bare metal.

Once it is bright enough:
A speaker that will play some kind of alarm sound
I2C camera that will take an image
UART display that will display the time when it reached the brightness
SPI expansion board that enables bluetooth, which should then allow me to send the image and timestamp over bluetooth

basic driver ideas from here https://www.youtube.com/watch?v=5cp2iPGWmUY&t=3290s&pp=ygUPZW1iZWRkZWQgZHJpdmVy0gcJCaMLAYcqIYzv
will be emulating on https://wokwi.com/, though not entirely accurate, it's slightly easier for me than to gather all the parts.
https://github.com/pauloborges/blessed
https://github.com/tinygo-org/bluetooth
