# Remote-Controlled-Car

*Note: This repo is just a demo for coding section, but does not have the functionality without the car and UBC internet connection*

### Contents Included:
 - Code on the car in python
 - Javascript on server for connection
 - other website files such as .html and .css

### Overall Mechanism:
- The user can control the car from the website using w, a, s, d keys
- The sensors on the car will keep track of distance in all four directions
- All sensor data will be updated synchronously on the web page
- Whenever one of them is within a dangerous distance range, the car will take a picture of what's in that direction
- The picture will be sent to the web page for the user, and the car will automatically go in opposite direction to run away from the obstacle

### Hardware Used
- Raspberry Pi 4
- DC motors
- Ultrasonic sensors
- Camera module
