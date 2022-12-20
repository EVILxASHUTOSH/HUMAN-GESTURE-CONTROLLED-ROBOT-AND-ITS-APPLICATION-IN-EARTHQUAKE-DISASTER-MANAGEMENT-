# HUMAN-GESTURE-CONTROLLED-ROBOT-AND-ITS-APPLICATION-IN-EARTHQUAKE-DISASTER-MANAGEMENT-
A robot that can be controlled using hand gestures, usefull for remote and emergency operations
Earthquakes are one of the most common and fatal natural 
disasters that cause massive damage to human lives and 
property. The aftermath of the earthquakes is just as brutal as 
the natural calamity itself but there are still chances of saving 
lives if there are survivors left and they are rescued from the 
property ruins before something worse happens. But it is quite 
difficult for humans to penetrate the building ruins to get to the 
survivors. It is even more difficult of knowing if there are any 
survivors at all. We have designed a robot that can be controlled 
by hand gestures that can pass through the cracks and ruins and 
reach the survivors. This gesture-controlled robot unit can be 
used to monitor the inside of the ruins by attaching a camera to 
the robot. The robot can also be fitted with an ultrasonic 
distance sensor to get an estimate of the approximate positions 
of the survivors. Our project will comprise two units: a remote 
unit and a mobile robotic car unit. This mobile robotic car unit 
will be controlled by the remote unit through hand gestures and 
will enter the ruins to reach the survivors. Arduino Uno, 
Arduino Nano, MPU - 6050, and HC-05 Bluetooth modules will 
be involved to make this project

## COMPONENTS REQUIRED:
1. ARDUINO UNO R3 - 1
2. ARDUINO NANO - 1
3. Car Chassis-1(plastic/wood)
4. Bluetooth module - 2
5. 9V batteries - 2
6. Power bank - 1
7. Jumper wires
8. Breadboard - 2
9. Stepper motor - 2
10. Wheels - 3
11. Gloves - 1 pair
12. Motor driver - 1 (L293D)
13. MPU6050 - 1

## HARDWARE IMPLEMENTATION:
(MOBILE ROBOTIC CAR UNIT)

 
![image](https://user-images.githubusercontent.com/77974948/208611682-96d8c5cf-af1f-4342-8666-8b0d8803e3ba.png)
![image](https://user-images.githubusercontent.com/77974948/208611711-c9144089-4c87-4b41-bbe9-baa6b24bc3bc.png)
![image](https://user-images.githubusercontent.com/77974948/208611739-098357cb-47dd-45ca-8fb9-12009733fc0e.png)
![image](https://user-images.githubusercontent.com/77974948/208611756-8b3bc4cf-01fa-46ae-b537-6880919f81a6.png)






All connections are properly shown in the figure given above. We have a motor driver that powers the 2 stepper motors onto which the wheels are attached.  The motor driver draws voltage from the power bank attached in front. The Bluetooth Module over here is the slave device or the receiver and the microcontroller used here is the Arduino Uno R3 which is powered by a 9V battery.


(REMOTE UNIT)
 
![image](https://user-images.githubusercontent.com/77974948/208611775-5aef34b4-e0d4-4202-9874-4fa26808331c.png)
![image](https://user-images.githubusercontent.com/77974948/208611793-d65dfc13-5984-4d66-aa01-53909b83f7d0.png)


 
For the Remote Unit, we have the MPU – 6050 which is the gyro sensor that is used to detect motion and human movement. The microcontroller used is the Arduino Nano R3 which is being powered by a 9V battery. The Bluetooth Module connected here is the master device or the Transmitter that transmits or sends data to the receiver or slave device that is connected to the robotic car unit.



## ROADMAP:
Thus, we have managed to successfully design what we had intended to do. The robotic car unit is fully functional and can move in various directions based on the movement of the hand. The Bluetooth devices are working properly even though there is a delay in the reception of the signal. The motor driver needs a lot of power to function, hence we used a power bank as 9V batteries were not enough. The MPU – 6050 allows the detection of human movement and the car unit moves in that direction. This system can be improved and enhanced further in order for it to be employed as a tool for earthquake disaster management

## License
Distributed under the MIT License. See LICENSE for more information.

## Contact
@EVILxASHUTOSH-dearashutoshmishra2002@gmail.com

Project link: 
