# Dice Workshop
A simple Arduino project that simulates a rolling die using an OLED display and a push button. When the button is pressed, the display     shows a rolling animation and outputs a random value from 1–6 on 2 dice.
  
Hardware Components:
  1. Arduino Nano
  2. OLED Display (128×64, I2C)
  3. Push Button
  4. Breadboard
  5. Jumper Wires

#Wiring: 
  1. OLED Display (I2C)
    - VCC: 5V
    - GND: GND
    - SDA: A4
    - SCL: A5
  2. Push Button
     - One leg: D2
     - Other leg: GND

Software Setup
  1. #Install the Arduino IDE
  2. #Install required libraries:
    - Adafruit SSD1306
    - Adafruit GFX
  3. #Connect your Arduino Nano
    - Select Board: Arduino Nano
    - Port: (your COM port)
  4. #Upload the code

How To Use:
1. Power the Arduino
2. Press the push button
3. Watch the dice roll animation
4. View the final result on the OLED
