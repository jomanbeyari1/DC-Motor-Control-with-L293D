# DC-Motor-Control-with-L293D

![Copy of L293D DC Motor Arduino (1) (2)](https://github.com/user-attachments/assets/42b8e7d6-d1f5-4378-9dc5-371339246fc9)

This project demonstrates how to control four DC motors using an Arduino board and the L293D motor driver. The motors are programmed to perform specific movements: moving forward for 30 seconds, backward for 60 seconds, and alternating between right and left for 60 seconds.

Components used:

1-Arduino UNO

2-L293D Motor Driver

3-Four DC Motors

Motor A:
Enable: enA (Pin 6)
Direction: in1 (Pin 7), in2 (Pin 4), 
Motor B:
Enable: enB (Pin 3)
Direction: in3 (Pin 5), in4 (Pin 2), 
Motor C:
Enable: enC (Pin 10)
Direction: in5 (Pin 8), in6 (Pin 9), 
Motor D:
Enable: enD (Pin 11)
Direction: in7 (Pin 12), in8 (Pin 13).

4-Breadboard and Jumper Wires

5-Power Supply (9V Battery)




And here is the code:
https://1drv.ms/t/c/9448f0a8866e182f/Eaj-cJIOChBBjoET2D6BVX0BJII_rnqQ-wkzTZbx7ZcmVw?e=xZ0W8d

This code is designed to control four DC motors using an Arduino and the L293D motor driver.

About the code in details:

1)-Pin Definitions:
The pins for motor control are defined:
enA, enB, enC, enD: These are the PWM control pins for speed for each motor.
in1, in2, in3, in4, in5, in6, in7, in8: These are the control pins for the direction of each motor.

2)- Setup: Initializes serial communication and sets motor control pins as outputs. All motors are turned off initially.

3)- Loop:
Moves forward for 30 seconds, 
Moves backward for 60 seconds, 
Alternates between turning right and left for 60 seconds.

4)- Movement Functions:
moveForward(): Activates motors to move forward, 
moveBackward(): Activates motors to move backward, 
moveRightLeft(): Alternates turning right and left at defined intervals.
stopMotors(): Stops all motors and adds a brief delay.
