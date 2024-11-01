# Ethos-Rotorflight
# Instructions to adjust PID's using a Frsky TX
This guide will assist in the setup of a Frsky Ethos based TX allowing you to adjust Rotorflight PID's in real time without landing to adjust, care must be taken to ensure you are in full control of the Aircraft when adjusting parameters

__NOTE: The PID settings will not be fully saved to eeprom untill you disarm the Heli using the ARM/DISARM switch__

## Transmitter Setup
Step1: You need to disable trims for Roll, Yaw and Pitch

![image](https://github.com/jimmy6616/Ethos-Rotorflight/blob/main/Trim1.jpg)

![imaage](https://github.com/jimmy6616/Ethos-Rotorflight/blob/main/Trim2.jpg)

Step2: Setting up the 6-Pos switch to allow control of the Paramters.
Add a VAR
![image](https://github.com/jimmy6616/Ethos-Rotorflight/blob/main/Var1.jpg)

Edit the VAR with the following values, these values will translate in the RF Adjustments tab to Select, FS1 is off, FS2 is 'P', FS3 is 'I', FS4 is 'D', FS5 is 'F' and FS6 is 'B'
![image](https://github.com/jimmy6616/Ethos-Rotorflight/blob/main/Var2.jpg)

Add a mixer for your chosen channel, in this example Ch 11 Called PID Enable with a source of the 6POS VAR. Also add 3 additional mixers for PID selection, in this example Ch12, 13 and 14.
![image](https://github.com/jimmy6616/Ethos-Rotorflight/blob/main/Mix1.jpg)

Step3: Setup each mixer for the Trim switches, Trim RVU and RVD for Pitch adjust, Trim RHR and RHL for Roll adjust and Trim LHR and LHL for Yaw adjust
![image](https://github.com/jimmy6616/Ethos-Rotorflight/blob/main/Mix4.jpg)
