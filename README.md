# stepofy-hardware
This PCB includes :
- an ESP32 that enable wifi/bluetooth communication link,
- microstep driver to rotate a stepper motor. Motor current can be controlled by software. This can be used for torque limitation.
- magnetic encoder to get realtime angle feedback. 
- I2C OLED interface
- 3 push button + reset.
- Serial interface for programmation
- mounting holes to be directly mounted on the back of a NEMA 17

Using torque control and feedback position capabilities, learning scenarios by directly moving the motor are possible.

Power supply from 8 to 12V.

![Stepofy V1](https://github.com/Smartdatalog/stepofy-hardware/blob/master/preview.jpg "Stepofy V1")

![Stepofy V1](https://github.com/Smartdatalog/stepofy-hardware/blob/master/v1/stepofy%20v1%20with%20motor.jpg "Stepofy with NEMA17")

# Current status
V1 prototype is under test. Schematic is available. 
See [V1 details](https://github.com/Smartdatalog/stepofy-hardware/tree/master/v1 "V1")

# Licence
Licence Comon Creative CC BY-NC-SA 4.0
Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)
https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode

You are free to:
- Share : copy and redistribute the material in any medium or format
- Adapt : remix, transform, and build upon the material

Under the following terms:
- Attribution : You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- NonCommercial : You may not use the material for commercial purposes.
- ShareAlike : If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
