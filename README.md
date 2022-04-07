# Light-Detector-Measuremet-
Masters Research Project Code


There are two files, a C program and a Python program. 

The C program runs on the Mbed platform and is intended to commmunicate with the F411RE Nucleo Microcontroller.
The C program reads measurements from a 3D detector system that has 8 arms with one UV and one visible light detector on each arm. 
The select lines S0, S1, S2 cycle through the arms one at a time to read the uv, visible (PD) diodes, and the state of the switch. 
Each arm has 8 possible horizontal positions. When the user has moved the arm to its next position, they should hit the user button for the program to read the measurments on all the arms again. 

TeraTerm is a good terminal the user should use on their computer to read the output of the C program. It is possible to save the data to a .log file using TeraTerm. 

The Python program should be adjusted to read directly from the .log file. 
The Python Program shifts the data using the switch information to print heat maps of the optical distribution and intensity where each measurement is mapped where the detectors were located when they took the measurement. 


