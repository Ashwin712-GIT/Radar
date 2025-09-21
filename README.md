This project outlines the development of a low-cost, real-time radar system using an Arduino microcontroller, an ultrasonic sensor, and a servo motor. 
The primary objective is to demonstrate the principles of object detection and data visualization by creating a system that detects objects and displays their location on a graphical user interface (GUI).
The hardware consists of an Arduino Uno (or ESP32), an HC-SR04 ultrasonic sensor to measure distance, and an SG90 servo motor to sweep the sensor across a 180-degree field of view.
The system is powered and communicates with a computer via a USB cable.
On the software side, the project uses two separate programs: an Arduino sketch and a Processing sketch. 
The Arduino sketch is responsible for controlling the servo's movement and reading the distance from the sensor. 
It then sends this data (angle and distance) to the computer via the serial port. 
The Processing sketch receives this data, uses trigonometry to convert it into visual coordinates, and draws a real-time radar display on the screen, complete with a sweeping line and points representing detected objects.
The project highlights the system's simple, yet effective, workflow and addresses common challenges like sensor accuracy and servo jitter. 
It also proposes improvements such as using a LiDAR sensor for better accuracy, integrating an ESP32 for wireless communication, and developing a more advanced GUI.
In essence, this project serves as a foundational exercise in embedded systems and data visualization, providing a hands-on learning experience for students and hobbyists interested in robotics and real-time sensing applications.
