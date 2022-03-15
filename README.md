# microwave-firmware
PIC18 Assembly code implementing firmware for a microwave oven
This project utilizes a PIC18 simulator program to simulate the operation of a microwave. A matrix keypad is connected to PORTB to provide timer input and control of the microwave. Single tens digit timer control is provided via Timer1. The matrix keypad also provides the ability to simulate the door opening. LEDs represent the magnetron (RA1) and buzzer (RA0). A safety interlock is in place to prevent the microwave from cooking while the door is open. 
