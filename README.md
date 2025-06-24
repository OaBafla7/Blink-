This is a simple Arduino project that blinks three LEDs (Red, Green, and Blue) in a sequential pattern. The project is a basic introduction to Arduino programming and digital output control.

Components Required
Arduino Uno

3 LEDs (Red)

3 x 100Ω resistors

Breadboard

Jumper wires

#Circuit Diagram
Connect the anode (long leg) of each LED to digital pins 8, 9, and 10 on the Arduino Uno through 220Ω resistors.

Connect the cathode (short leg) of each LED to the GND (Ground) on the Arduino.

Code Explanation
The Arduino sketch (three_led_blink.ino) does the following:

Turns on each LED one after another with a 1-second delay.

Turns them off in the same sequence.

Repeats the process in a loop.

#Code Explanation
The Arduino sketch (three_led_blink.ino) does the following:

Turns on each LED one after another with a 1-second delay.

Turns them off in the same sequence.
Repeats the process in a loop.

#How to Use
Upload the code to your Arduino Uno.

Observe the LEDs blinking in sequence (Red → Green → Blue).

Troubleshooting
If an LED doesn't light up, check the connections (polarity and resistor).

Ensure the correct pins are defined in the code.

Author
[Omar Abdulrahman Baflah]

License
This project is open-source and free to use.
