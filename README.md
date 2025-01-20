# Obstacle Avoidance Robot

** The obstacle Avoidance Robot** is a   robot that uses an **ultrasonic sensor** to sense obstacles, and send information to the Arduino board. The **Arduino uno board** receives the information, runs calculations based on instructions given to it by the programmer, these instructions (codes) were written using the **Arduino Ide** software and controls how to sense the obstacle, when to move the Robot and how the Robot should move.



## Components Of the Obstacle Avoidance Robot
### 1) Arduino uno board:
This is the Most important part of the Obstacle Avoidance Robot. It controls the activities of the Robot, receives information from it's **Input Pins** and send out voltage through it's **Output Pins**, thought it sounds simple, this basic functions is like a portal to a world of endless possibilities

### 2) Ultrasonic Sensor:
The ultrasonic Sensor is the eyes of the Obstacle Avoidance Robot. It senses the environment by sending out **Ultrasonic Waves** and measuring the Time taken for the wave to get back to it. This ** Time Taken** is what is used by the Arduino board to calculate the distance.

### 3) Motor Driver (L298N):
This is the component that allows for the Arduino board to control the direction of rotation of the wheels, and the speed of the rotation of the wheels individually.

### 4) DC-Motors: 
This is the electrical components that rotate to move the wheels which in turn caries the robot forward, backwards and turns it in the required direction.

### 5) Liquid Crystal Display:
The LCD screen serves as a means to communicate information to the observer. The distance, and the movement of the robot is displayed on the LCD screen.

### 6) Proteus 8 Professional:
This is an application software that allows to design and simulate the Obstacle Avoidance Robot, boycotting the cost of getting components, trials and errors, and unforseen mistakes during the connections and Programming.



## Working Principle Of Obstacle Avoidance Robot
The Ultrasonic Sensor sends out Ultrasonic sound wave, this sound wave hits an obstacle and bounces back, the ultrasonic sensor measures the time taken for the Echo to get back to it. This information is sent to the Arduino board which calculates the distance based on a formula embedded in the instruction set for it (C++ code).
The Arduino board Controls the motors through the motor driver according to the Functions in the code(to avoid the obstacle).



## Limitations of the Obstacle Avoidance Robot
Due to the ultrasonic sensor used, the ** Obstacle Avoidance Robot** can't sense object too close to it, and to far away,The accuracy can be affected by environmental conditions such as temperature, humidity, and air pressure, which can change the speed of sound, it may have difficulty detecting soft, absorbent, or angled surfaces because such surfaces might absorb the sound waves or reflect them away from the sensor.
Overall, the **Obstacle Avoidance Robot** shares the same limitations as the **Ultrasonic Sensor**




## Resources And References
www .hackatronic.com
www.google.com
www.researchgate.net
www.microsonic.de
www.robocraze.com
www.sonimat.com



## Contributors and Contact Information

### Olaniyi Oluwatobiloba:
Whatsapp: +2348142254429
Phone: +2349063627019

### Idowu Iremide:
Whatsapp: +234 814 621 3147
Phone: +234 814 621 3147

### Ikewun David:
Whatsapp: +234 912 325 5939
Phone: +2349155409945

### Abolarin Oluwajomiloju:
Whatsapp:+234 901 133 8466
Phone::+234 901 133 8466

### Ibironke Priscilla:
Whatsapp:+234 702 663 1261
Phone:+234 702 663 1261

 
