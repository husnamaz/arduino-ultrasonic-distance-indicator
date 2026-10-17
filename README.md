Arduino-Based Ultrasonic Distance Indicator

About the Project:

This project uses an Arduino Uno and an ultrasonic sensor to detect the distance of an object and indicate its proximity through three LEDs: red, yellow, and blue.

I built this project to gain hands-on experience with sensor interfacing, Arduino programming and distance-based control. I also worked with circuit simulation in Tinkercad to understand and test the system's behaviour.

Components Used:
- Arduino Uno
- HC-SR04 ultrasonic sensor
- Red, yellow, and green LEDs
- Breadboard and jumper wires
- Current-limiting resistors for LEDs

Pin Configuration:
Component| Arduino Pin
Trig pin| 8
Echo pin| 9
Red LED| 7
Yellow LED| 6
Green LED| 5

How It Works:

The ultrasonic sensor sends a sound pulse and measures the time taken for the echo to return. The Arduino uses this time to calculate the distance in centimetres and controls the LEDs according to the measured range.

- Red LED: Distance up to 10 cm
- Yellow LED: Distance above 10 cm and up to 25 cm
- Blue LED: Distance above 25 cm
- No LED: When no valid echo is detected

The distance readings are also displayed in the Serial Monitor at 9600 baud.

Tools Used

- Arduino IDE
- Tinkercad Circuits

What I Learned

Through this project, I practised working with ultrasonic sensors, reading sensor data, using conditional statements, and controlling multiple LEDs through Arduino. It also gave me an opportunity to connect programming concepts with a practical electronics project.

Future Improvements

I would like to extend this project by adding a buzzer for proximity alerts or an LCD to display the measured distance.

---

Project Area: Embedded Systems | Arduino | Sensor Interfacing

Institution: University of Engineering and Technology (UET), Lahore
