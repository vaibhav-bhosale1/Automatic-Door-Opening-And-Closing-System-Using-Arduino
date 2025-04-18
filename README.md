# Automatic-Door-Opening-And-Closing-System-Using-Arduino
The Automatic Door Opener System, employing a PIR or IR Sensor with Arduino, detects individuals in close proximity and automatically opens/closes doors, a technology commonly seen in malls and hospitals. These systems slide doors open upon approach (within 2-3 feet) and close after a brief delay (5-10 seconds) unless continuous movement is detected. Offering convenience and noise reduction, they eliminate the need for manual door operation and the role of a doorman. Arduino-based Automated Door Opener projects provide practical insights into automatic door mechanisms, applicable in various settings like garages, toilets, and offices.

working of circuit:
The circuit operates in two ways, utilizing either a PIR sensor or an IR sensor for object detection. The primary difference lies in their detection methods—IR relies on wave reception, while PIR detects energy level differences. The circuit, demonstrated with an IR sensor, connects the sensor to the ground, 5V Vcc, and a digital pin. A servo motor, linked to ground, Vcc, and another digital pin (9), controls a cardboard piece mimicking a door. Optional elements like LED or LCD modules can indicate object detection. The Arduino code adjusts the servo angle based on sensor output, simulating door movement. A delay ensures the door remains open if further movement is detected within a specified timeframe.

components required:
1. Arduino UNO 
2. Servo Motor 
3. Infrared Proximity Sensor 
4. Cardboard Door 
5. Power Supply 
6. Led 
7. USB A to B Cable 
8. Breadboard

I have given pin diagram and other necessary information to implement this project in my report and i have also provided arduino code with comments to understand.
