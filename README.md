##﻿Desktop Braille Printer##

Desktop braille printing machine is designed to print braille script on a piece of paper. The main mechanism is embossing dots in the paper using a pointed pin type actuator.

![IMG-20240329-WA0007](https://github.com/fablabnepal1/Desktop-Braille-Printing-Machine/assets/140875358/967ec639-ef22-453c-ac73-73f3ae72a742)

Here are some major features of the braille printing machine.
* Use of tinyG(ATMLE xmega192a3u) hardware as a controller for the machine.
* 2 stepper motors for x and y axis,
* Accepts Gcode from USB ports and interprets it.
* A solenoid linear actuator is used to emboss braille dots into the paper.
* Use of chillipeppr to visualize work on progress.
See these links for more details
Mechanical Components 
The braille printer consists of different mechanical components such as housing, belts, and pulleys.
  


1. System Box and Housing
2. Controller box
3. Shaft, Pulley and Belts
4. Supporting Parts 


Electronic components
The main controller is TinyG along with other accessories. The basic electronic components are: 
1. TinyG v8 board
![IMG_20231219_122103](https://github.com/fablabnepal1/Desktop-Braille-Printing-Machine/assets/140875358/e2b8dbd6-7227-4506-8693-3de63a77864b)
 
2. Nema17 motors
![viber_image_2024-04-03_12-56-43-995](https://github.com/fablabnepal1/Desktop-Braille-Printing-Machine/assets/140875358/d90e1a80-e6d4-476e-b084-12f240e180e0)


3. Relay switch
![IMG_20231219_143317](https://github.com/fablabnepal1/Desktop-Braille-Printing-Machine/assets/140875358/dfcf89a0-e8ca-4e05-8edb-7aafdb7922b2)


Operating Steps
After the machine has been assembled, the following steps are done to print on braille script:


1. Use Braillerap to generate Gcode  
2. Conditioning and reviewing Gcode for correctness.
3. Power the braille printer and connect it to the interface.
4. Load Gcode into the interface and send it to the machine.
5. Load the paper, manage it, and print on the paper.
