# Version 1.2 improvements

INO code development improvements to ArduinoDueArbitraryWaveformGeneratorAndController Version 1.2. 
These include addition of User Defined Equation code modifications and parameters which builds upon and increases functionality 
with custom wave shapes and control using the Arduino Due Serial Monitor. There are now 7 wave shapes included (sine, triangle, arbitrary, 
staircase, square root, ring modulator and pseudo noise) each with custom variables (e.g. wave amplitude, phase shift, vertical shift, etc.) 
including a sample and hold function capability which can be changed within the Serial Monitor. 
Changing variables and functions will modify the output wave shape. 

To use:
1) Upload this sketch to Arduino Due.
2) The analogue wave output is taken from DAC0. 
3) In the Serial Monitor type "x" and then press "Enter" to access Extra commands for each wave shape.

Example Serial Monitor commands:  Type x0 then Press enter. This will show you a list of all variables you can change on the sine wave in the Serial Monitor. To change a variable, the Serial Monitor command format is number then variable command (i.e. try -0.5 as the number and x0a is the command for sine wave amplitude). So in the Serial Monitor type -0.5x0a and press enter to change the variable for sine amplitude which will reduce the amplitude and invert the wave. Then type xx and press enter to update all waves with all variable changes. Type w to change to other wave forms. For more commands type ? and press enter.


Analogue wave max freq: 100kHz. Square wave max freq: 42MHz. Duty cycle adjustable from 0% to 100%
