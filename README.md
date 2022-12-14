# esp32_cam_electric_watergun
 esp32 camera for remote control electric wategun

This code is based on the random nerd tutorials tutorial on using an esp32-cam with a pan tilt mechanism. I've just added around four lines to control the water gun.
https://randomnerdtutorials.com/esp32-cam-pan-and-tilt-2-axis/

I’ve attached this electric water gun to a camera pan tilt mechanism, and on top of the water gun I’ve placed an esp32 cam, which controls the servos and firing mechanism for the water pistol, and outputs to a web interface, which is shown in the bottom right of the screen. In the rest of this video I’m going to go through the steps for making this project.

TB6612FNG motor driver connections
Motor Driver	  Connected to
GND	           GND
AIN1	          GND
AIN2	          ESP32 pin 12
STDBY	         ESP32 pin 12
PWMA	          ESP32 pin 12
AO2	           Positive input of water gun
AO1	           Negative input of water gun
Vcc	           ESP32 3.3v
Vm	            6-7 volts from the LM2596 buck converter

Links Referenced in the video:

Random Nerd Tutorial pan-tilt tutorial
https://randomnerdtutorials.com/esp32-cam-pan-and-tilt-2-axis/ 

Thingverse stl files for pan-tilt mechanism used in this project
https://www.thingiverse.com/thing:1401116 

Parts List:

Electric Water Gun
https://www.amazon.com.au/gp/product/B09XDLMXBK/ 

ESP32-cam
https://www.aliexpress.com/item/4001133770461.html 

LM2596 DC to DC Voltage Regulator 3.0-40V to 1.5-35V Buck Converter DIY Power Supply Step-Down Module
https://www.amazon.com.au/gp/product/B076H3XHXP/

TB6612FNG Motor Driver
https://www.aliexpress.com/item/32223093678.html 

Servos
https://www.aliexpress.com/item/1005003529427455.html 

Battery Connectors
https://www.aliexpress.com/item/1005003469527490.html 

