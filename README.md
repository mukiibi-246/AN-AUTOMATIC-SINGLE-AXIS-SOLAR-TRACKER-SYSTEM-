# AN-AUTOMATIC-SINGLE-AXIS-SOLAR-TRACKER-SYSTEM-
DESIGN AND CONSTRUCTION OF AN AUTOMATIC SINGLE AXIS SOLAR TRACKER SYSTEM 
 Design and Construction of an Automatic Single Axis Solar Tracker System
 
PROJECT TITLE 
Design and Construction of an Automatic Single Axis Solar Tracker System
PROBLEM 
Conventional fixed solar panels remain in one position throughout the day and cannot continuously face the sun. As a result, they receive less sunlight, reducing the amount of electrical energy generated. In addition, users cannot conveniently monitor the system remotely or keep a record of system data.
 SOLUTION 
This project uses an ESP32 microcontroller, two LDR sensors, a servo motor, a 16×2 LCD display, and an SD card module to automatically track the sun along a single axis ( from East  to  West) to improve energy capture throughout the day  . The ESP32 connects to a Wi-Fi network and hosts a web dashboard where users can monitor system parameters after logging in. The LCD displays system status and the assigned IP address, while the SD card stores the recorded data for future reference.

SETUP INSTRUCTIONS
1. Gather the required components:
   - ESP32 Development Board
   - Two LDR sensors
   - Servo motor
   - Solar panel
   - 16×2 LCD display
   - SD card module with a micro SD card
   - Resistors
   - Breadboard and jumper wires
   - Power supply

2. Assemble the circuit according to the circuit diagram.
3. Open the project in the Arduino IDE and upload the program to the ESP32.
4. Turn on the mobile hotspot (or Wi-Fi network) whose SSID and password are configured in the ESP32 program.
5. Power on the solar tracker system.
6. Wait for the ESP32 to connect to the Wi-Fi network. The LCD will display the assigned IP address.
7. Connect another phone or computer to the same Wi-Fi network.
8. Open a web browser and enter the IP address displayed on the LCD.
9. Log in to the web dashboard using:
   - Username: **SAST**
   - Password: **2026**
10. After logging in, the web dashboard displays the system parameters in real time. The system automatically rotates the solar panel toward the direction of maximum sunlight while displaying information on the LCD and storing data on the SD card.

