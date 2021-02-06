# Autonomous_RC_Car

February 2021

Inspired by: https://www.youtube.com/watch?v=1n_KjpMfVT0 

Youtube Demonstration: https://youtu.be/u6Tx4LFk9bU

Pictures Link: https://drive.google.com/drive/folders/1gyft5jYFw8f-CUI8NYlk71yFCflyTatb?usp=sharing 

This RC Car system is composed of an Arduino uno with a L293D Motor Drive Shield Expansion Board attached to the top of the Arduino. There is also a servo motor (SG90 9G Servo Motor) and a ultrasonic distance sensor (HC-SR04), all powered by a battery pack (12V AA circuit). All of this hardware is placed on a RC car chassis. 

The RC car accelerates forward and the ultrasonic distance sensor continuously detects how far away the car is from the closest surface. WHen that distance goes under 25cm the car stops. Moves backwards. Then the servo motor is involved and turns left and then right. The ultrasonic sensor, being attached to the top of the servo motor, also "looks'' left and right. The arduino then decides which side (whether left or right) has more space. The car then runs one of two methods. The car either turns left or right and then proceeds in that direction. This cycle continues as long as the car is on.

Challenges:

A big challenge was to fit all of the components onto the car and manage all of the wiring. The code for turning the car was really difficult because of the physics of which wheels would turn in which direction in order to turn the right way.

Lessons:

Working with a servo motor for the first time was very useful because servo motors are often used in projects like these. The new motor shield also allowed for 4 motors to be used as opposed to 2 motors from my hand gesture controlled RC car project.

Possible Improvements: 

The car doesn't deal with corners great because of the limits of the sensors is definitely something that could be improved. I also think the servo motor could be better utilized with a wider range of motion. 
