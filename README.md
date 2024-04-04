# Desktop Braille Printer

Desktop braille printing machine is designed to print braille script on a piece of paper. The main mechanism is embossing dots in the paper using a pointed pin type actuator.

![IMG-20240329-WA0007](https://github.com/fablabnepal1/Desktop-Braille-Printing-Machine/assets/140875358/967ec639-ef22-453c-ac73-73f3ae72a742)

Here are some major features of the braille printing machine.
* Use of tinyG(ATMLE xmega192a3u) hardware as a controller for the machine.
* 2 stepper motors for x and y axis,
* Accepts Gcode from USB ports and interprets it.
* A solenoid linear actuator is used to emboss braille dots into the paper.
* Use of chillipeppr to visualize work on progress.


**Mechanical Systems**
  
The braille printer consists of different mechanical components such as housing, belts, and pulleys.

1. System Box and Housing
2. Shafts and  Paper Rollers
3. Bearing and Housing
4. Pulley and Belts
5. Rails and Pulleys
6. Linear bearing and Housing
7. Linear Actuator Support

**Electronic Systems**

The main controller is TinyG along with other accessories. The basic electronic components are: 

1. TinyG v8 board
2. Controller box
3. Nema17 motors and parameters
4. Solenoid Linear actuator
5. Relay switch

**Working with Interfaces**
1. Coolterm
2. Chillipeppr
3. CNCJS

**Tests and Refinements**

