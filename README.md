# chord-controller

The scope of the project is to build a one handed music controller. The left side of the controller has an array of chosen root notes assorted based on the circle of fifths. Once the root note is chosen, the controller allows you to pick notes from that scale using modifiers. 

This is documenting the progress of building a chord based music controller. 
If you have any questions comments, send them to eforzano@gmail.com. 


## Handling Inputs and Outputs 

There seems to be many ways to handle many inputs and outputs. These three resources with the most helpful in me making my decision: 

- [Input Matrix Scanning](http://www.openmusiclabs.com/learning/digital/input-matrix-scanning/) - Background on Input matrix Scanning and other ways to create music controllers
- [Microcontroller input and output expansion](http://www.st.com/content/ccc/resource/technical/document/application_note/38/85/01/85/d2/2d/4d/45/CD00165404.pdf/files/CD00165404.pdf/jcr:content/translations/en.CD00165404.pdf)  - a  White paper on the ways to expand inputs and outputs
- [Monome layout](https://github.com/monome/40h) - Github Repo on how the Monome accomplished this 
- [DIY Fake Launchpad](https://www.youtube.com/watch?v=4DVGBVvvFgQ) - YouTube tutorial on making Fake launchpad

## Bought Materials

- 4x4 PCB Matrix 
- 100 RGB LEDs 
- 30 1N4148 Diodes 
- PCB Button Pad 
- 74HC165 Parallel-to-serial shift registers - for the Buttons 
- 74HC595 Serial-to-Parallel Shift Registers for the LEDs


Going to attempt to attach with Breadboard. 

## Approach

Going to use breadboard the 4x4 PCB Matrix and drive LEDs with the 74HC165

<!---
- 10K ohm 5-pin array resistor
- 100 ohm resistor 
- TD62783 Darlington Transistor Source Driver
- 0.1nF capacitor
- max7219
-->
## Resources Index

- [SparkFun Hook-Up Guide](https://learn.sparkfun.com/tutorials/button-pad-hookup-guide?_ga=2.138974387.1213955471.1524700526-1942233505.1524700526#the-4x4-rgb-button-pad) - Explanation of Sparkfun's 4x4 Breakout Pad 
- [Wikipedia - Isomorphic Keyboard](https://en.wikipedia.org/wiki/Isomorphic_keyboard) - Wikipedia article Describing Isomorphic Keyboards 
- [Alt-Keyboards - Isomorphic Keyboards](http://www.altkeyboards.com/instruments/isomorphic-keyboards) - Alternative Keyboards Blog describing types of keyboards
- [Input Matrix Scanning](http://www.openmusiclabs.com/learning/digital/input-matrix-scanning/) - Background on Input matrix Scanning and other ways to create music controllers
- [Multiplexing with Arduino and the 74HC595](http://www.instructables.com/id/Multiplexing-with-Arduino-and-the-74HC595/) - Instructable about Multiplexing
- [Microcontroller input and output expansion](http://www.st.com/content/ccc/resource/technical/document/application_note/38/85/01/85/d2/2d/4d/45/CD00165404.pdf/files/CD00165404.pdf/jcr:content/translations/en.CD00165404.pdf)  - a  White paper on the ways to expand you 
- [Monome layout](https://github.com/monome/40h) - Github Repo on how the Monome accomplished this 
