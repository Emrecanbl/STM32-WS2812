STM32 WS2812 LED Controller
This project demonstrates how to control WS2812 LEDs using an STM32 microcontroller. The system is designed to generate various lighting effects and patterns on WS2812 LEDs.

Features
STM32 Microcontroller: Core processing unit for controlling WS2812 LEDs.
WS2812 LEDs: Individually addressable LEDs capable of displaying a wide range of colors.
Lighting Effects: Various predefined lighting effects and patterns.
Real-time Control: Efficient control using DMA and timers.
Components
STM32 Microcontroller (e.g., STM32F401)
WS2812 LED Strip
Power Supply (suitable for the number of LEDs used)
Connecting wires and resistors (as needed)
Installation
Clone the repository:

git clone https://github.com/Emrecanbl/STM32-WS2812.git
Open the project:
Open the project in your preferred IDE (e.g., STM32CubeIDE).

Configure the environment:

Ensure that the project is set up with the correct STM32 microcontroller configuration.
Configure the necessary peripherals (e.g., DMA, timers) for controlling WS2812 LEDs.
Compile and upload:
Compile the code and upload it to your STM32 microcontroller using a suitable programmer (e.g., ST-Link).

Usage
Connect the WS2812 LEDs:

Connect the data pin of the WS2812 LED strip to the configured GPIO pin on the STM32 microcontroller.
Connect the power and ground pins of the LED strip to a suitable power source.
Power on the system:
Ensure that the STM32 microcontroller and WS2812 LEDs are properly powered.

Initialize the system:
The microcontroller will automatically start controlling the WS2812 LEDs, displaying the predefined lighting effects.

Modify lighting effects:
You can modify the lighting effects by editing the code and adjusting the patterns and colors as needed.

Lighting Effects
The project includes various predefined lighting effects, such as:

Solid Colors: Display a single color on all LEDs.
Color Wipe: Sequentially change the color of each LED.
Rainbow Cycle: Display a rainbow of colors that cycles across the LEDs.
Theater Chase: Create a theater marquee effect with chasing lights.
Custom Patterns: Define your own patterns and effects.
Troubleshooting
LEDs Not Lighting Up: Check the connections and ensure the power supply is adequate for the number of LEDs.
Incorrect Colors or Patterns: Verify the configuration and timing settings for the WS2812 LEDs.
Microcontroller Issues: Ensure the code is correctly compiled and uploaded to the STM32 microcontroller.
Contributing
Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments
Special thanks to the open-source community and the developers of the libraries and tools used in this project.


