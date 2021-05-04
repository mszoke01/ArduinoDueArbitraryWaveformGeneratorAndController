# Version 1.2 improvements

INO code development improvements to ArduinoDueArbitraryWaveformGeneratorAndController Version 1.2. 
These include addition of User Defined Equation code modifications and parameters which builds upon and increases functionality 
with custom wave shapes and control using Serial Monitor. There are now 7 wave shapes included (sine, triangle, arbitrary, 
staircase, square root, ring modulator and pseudo noise) each with variables (e.g. wave amplitude, phase shift, vertical shift, etc.) 
including a sample and hold function capability which can be changed within the Serial Monitor. 
Changing variables and functions will modify the output wave shape. 

To use:
1) Upload this sketch to Arduino Due.
2) The analogue wave output is taken from DAC0. 
3) In the Serial Monitor type "x" and then press "Enter" to access Extra commands for each wave shape.

Analogue wave max freq: 100kHz. Square wave max freq: 42MHz. Duty cycle adjustable from 0% to 100%
