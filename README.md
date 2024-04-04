# Desktop Braille Printer

Desktop braille printing machine is designed to print braille script on a piece of paper. The main mechanism is embossing dots in the paper using a pointed pin type actuator.

![IMG-20240329-WA0007](https://github.com/fablabnepal1/Desktop-Braille-Printing-Machine/assets/140875358/967ec639-ef22-453c-ac73-73f3ae72a742)

Here are some major features of the braille printing machine.
* Use of tinyG(ATMLE xmega192a3u) hardware as a controller for the machine.
* 2 stepper motors for x and y axis,
* Accepts Gcode from USB ports and interprets it.
* A solenoid linear actuator is used to emboss braille dots into the paper.
* Use of chillipeppr to visualize work on progress.
See these links for more details

**Mechanical Components **
  
The braille printer consists of different mechanical components such as housing, belts, and pulleys.

1. System Box and Housing
2. Controller box
3. Shaft, Pulley and Belts
4. Supporting Parts 


**Electronic components**

The main controller is TinyG along with other accessories. The basic electronic components are: 
1. TinyG v8 board
2. Nema17 motors
3. Relay switch
4. Solenoid Linear actuators



**Operating Steps**

After the machine has been assembled, the following steps are done to print on braille script:


1. Use [Braillerap](https://crocsg.github.io/BrailleRap/) to generate Gcode  
2. Conditioning and reviewing Gcode for correctness.
3. Power the braille printer and connect it to the interface.
4. Load Gcode into the interface and send it to the machine.
5. Load the paper, manage it, and print on the paper.
