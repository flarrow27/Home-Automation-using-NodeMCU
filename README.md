# Home Automation using NodeMCU

This project demonstrates how to build a smart light control system using ESP8266 microcontroller, a 4V relay module, and light bulbs. The system allows users to remotely control the lights via Wi-Fi using a mobile app or web interface.

## Components

- ESP8266 microcontroller
- 4V relay module
- Light bulbs (3 units)
- Jumper wires
- Power supply

## Wiring

- Connect the ESP8266 pins to the corresponding pins on the relay module and light bulbs:
  - Pin 5 (D1): Relay module input 1
  - Pin 4 (D2): Relay module input 2
  - Pin 14 (D5): Relay module input 3
  - Pin 12 (D6): Relay module input 4 (if using a 4-channel relay module)
- Connect each light bulb to the output of the relay module.

## Installation

1. Clone this repository to your local machine or download the code files.

2. Open the code in the Arduino IDE.

3. Upload the code to your ESP8266 board.

## Usage

1. Ensure that the ESP8266 is connected to the Wi-Fi network.

2. Access the mobile app or web interface to control the lights remotely.

3. Toggle the switches in the app or interface to turn the lights on or off.

## Additional Features

- Timer Functionality: Implement timer functionality to schedule when the lights should turn on or off automatically.
- Voice Control: Integrate voice control using services like Amazon Alexa or Google Assistant.

## Contributing

Contributions to this project are welcome! Feel free to submit bug reports, feature requests, or pull requests via GitHub.

## Acknowledgements

- Thanks to the Arduino and ESP8266 communities for their support and resources.
- Special thanks to the developers of the libraries used in this project.

## Contact

For any inquiries or support, please contact jabinjoshua.s@gmail.com.

---

Upgrade your home lighting with the ESP8266 Smart Light Control System!
