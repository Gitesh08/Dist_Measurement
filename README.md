# Distance Measurement 📏

Arduino program that measures the distance to an object using an ultrasonic sensor and displays the result on a 16x2 LCD. 🚀

## Features 🌟
- Uses an HC-SR04 ultrasonic sensor to measure distance. 📡
- Displays real-time distance in centimeters on a 16x2 LCD. 🖥️
- Updates the distance reading every 250 milliseconds. ⏱️
- Built for Arduino-compatible boards. 🔌

## Requirements 🛠️
- Arduino board (e.g., Arduino Uno) 🖼️
- HC-SR04 ultrasonic sensor 📡
- 16x2 LCD with compatible interface 🖥️
- Arduino IDE 💻
- LiquidCrystal library 📚

## Hardware Connections 🔗
- **Ultrasonic Sensor**:
  - Trig pin: Arduino pin 13
  - Echo pin: Arduino pin 12
- **LCD**:
  - RS: Arduino pin 11
  - EN: Arduino pin 10
  - D4-D7: Arduino pins 2, 5, 3, 4 respectively

## Usage 🚀
1. Connect the ultrasonic sensor and LCD to the Arduino as described. 🔌
2. Upload the code to your Arduino using the Arduino IDE. 💾
3. The LCD will display "Target Distance:" on the first row and the measured distance in cm on the second row, updating every 250ms. 📊
4. Power the Arduino to start measuring distance. ⚡️

## Limitations ⚠️
- Accurate for distances up to ~400 cm (HC-SR04 sensor limitation). 📏
- Requires a stable power source for reliable readings. 🔋
- LCD display limited to 16x2 characters. 🖥️
