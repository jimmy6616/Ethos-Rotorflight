# Ethos-Rotorflight
# Instructions to adjust PID's using a Frsky TX
This guide will assist in the setup of a Frsky Ethos based TX allowing you to adjust Rotorflight PID's in real time without landing to adjust, care must be taken to ensure you are in full control of the Aircraft when adjusting parameters

__NOTE: The PID settings will not be fully saved to eeprom untill you disarm the Heli using the ARM/DISARM switch__

## Transmitter Setup
Step1: You need to disable trims for Roll, Yaw and Pitch

![image](https://github.com/jimmy6616/Ethos-Rotorflight/blob/Img/Trim1.jpg)

![imaage](https://github.com/jimmy6616/Ethos-Rotorflight/blob/Img/Trim2.jpg)

Step2: Setting up the 6-Pos switch to allow control of the Paramters.
Add a VAR
![image](https://github.com/jimmy6616/Ethos-Rotorflight/blob/Img/Var1.jpg)

Edit the VAR with the following values, these values will translate in the RF Adjustments tab
![image](https://github.com/jimmy6616/Ethos-Rotorflight/blob/Img/Var2.jpg)

Add a mixer for your chosen channel, in this example Ch 11 Called PID Enable with a source of 6POS
![image](https://github.com/jimmy6616/Ethos-Rotorflight/blob/Img/Mix1.jpg)
