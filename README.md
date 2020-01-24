# **Object Sorting Using Robotic arm and Image processing**

## Overview :- 


1. The object should be placed *(as shown in the video)* in **between the clamp in front of the camera which will be sorted depending upon the color of the object. The robotic arm will place them at three different angles at 90,180 and 270 degrees**. The USB camera which is connected to the Raspberry PI continuously scans the live feed for an colored object.


2. Raspberry Pi will detect the color of the object using Image Processing. The colors used in this project are Red, Green and Yellow. Colors can be added by modifying the code.


3. RPI is connected to an Arduino Uno board using two Jumper wires which will send the information to arduino board using 2 bit communication method. The color is represented by binary numbers.
For Eg:- Red is represent as 10, Green as 01 and Blue as 11 where 1 is **HIGH (5 volt)+++++** and 0 is **LOW (0 volt)**.

4. The two wires will be connected from GPIO pins of Rpi to two digital pins of arduino using simple jumper wires.

5. The robotic arm will perform operation depending upon the color.


6. Arduino will control three servo motors and motor control clamp. 



  
**HARDWARES USED:**


1. RASPBERRY PI 2


2. ARDUINO UNO


3. USB CAMERA


4. MOTOR CONTROL I.C. (For clamp in robotic hand)


5. Three SERVO MOTORS




**SOFTWARES USED:**


1. PYTHON


2. OPENCV


3. ARDUINO IDE


4. NUMPY


**How to run the bot..?**


1. Run **classmoto.ino** in Arduino board which controls two servo motors and a dc motor.


2. Run **colordetect.py** on Raspberry pi which is connected with a USB camera.

3. Ensure the two jumper cables are connected to desired pins by referring the source code.





 
