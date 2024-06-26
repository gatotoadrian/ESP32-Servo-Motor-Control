# ESP32 Servo Motor Control

This project demonstrates how to use an ESP32 to control a servo motor. The servo motor rotates back and forth between 0 and 180 degrees, showcasing how to perform precise angle control using the `ESP32Servo` library.

## Requirements

- ESP32 board (NodeMCU-32S or similar)
- Servo motor
- Arduino IDE with ESP32 board support

## Libraries

Make sure to install the necessary libraries via the Arduino Library Manager:
- `ESP32Servo`

## Hardware Setup

1. **Servo Motor Connections:**
   - VCC to 5V
   - GND to GND
   - Signal pin to GPIO 26
