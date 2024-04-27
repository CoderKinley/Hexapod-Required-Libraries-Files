# Hexapod Required Arduino IDE Libraries

## Overview
This repository contains a collection of Arduino libraries required for building and programming a hexapod robot. Each library serves a specific purpose in controlling various components of the hexapod.

## Libraries

### 1. ACROBOTIC_SSD1306
- **Description**: Library for controlling SSD1306 OLED displays by Acrobotic.
- **Usage**: Ideal for displaying information on OLED screens in hexapod projects.

### 2. Adafruit_BusIO
- **Description**: Library providing an abstracted interface to communicate with I2C and SPI devices by Adafruit.
- **Usage**: Enables seamless communication with I2C and SPI devices, essential for sensor integration.

### 3. Adafruit_GFX_Library
- **Description**: Graphics library providing a common set of graphics primitives (points, lines, circles, etc.) for various displays by Adafruit.
- **Usage**: Facilitates graphic rendering on displays, useful for visual feedback and debugging.

### 4. Adafruit_PWM_Servo_Driver_Library
- **Description**: Library for controlling PWM servos using Adafruit's PWM/Servo Driver.
- **Usage**: Enables precise control of PWM servos, crucial for controlling leg movements in hexapod robots.

### 5. Adafruit_SSD1305
- **Description**: Library for controlling SSD1305 OLED displays by Adafruit.
- **Usage**: Similar to ACROBOTIC_SSD1306, suitable for interfacing with SSD1305 OLED screens.

### 6. Adafruit_SSD1306
- **Description**: Library for controlling SSD1306 OLED displays by Adafruit.
- **Usage**: Essential for controlling OLED displays in hexapod projects, offering easy-to-use functions.

### 7. Bounce2
- **Description**: Library for debouncing digital inputs by Thomas Ouellet Fredericks.
- **Usage**: Ensures reliable detection of button presses and other digital inputs, enhancing user interaction.

### 8. PCA9685-Arduino-master
- **Description**: Library for controlling PCA9685 PWM/Servo drivers.
- **Usage**: Interfaces with PCA9685 PWM/Servo drivers, allowing for precise servo control and motion coordination.

### 9. RF24
- **Description**: Library for NRF24L01(+) transceiver modules by TMRh20.
- **Usage**: Facilitates wireless communication between hexapod components, enabling remote control or coordination with other devices.

### 10. ezButton
- **Description**: Library for handling button presses and debouncing by Brian T. Parkin.
- **Usage**: Simplifies the integration of buttons in hexapod control interfaces, ensuring accurate input recognition.

## Installation
To use these libraries in your Arduino IDE:
1. Download the repository.
2. Add each library to your Arduino libraries folder.
3. Include the desired libraries in your Arduino sketches using `#include <LibraryName.h>`.

## Contribution
Contributions to this repository are welcome. If you encounter any issues or have suggestions for improvement, feel free to submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
