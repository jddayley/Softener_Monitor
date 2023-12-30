 # Water Softener Salt Pellet Fullness Detector

## Project Overview
This repository hosts the code and documentation for an IoT-based Water Softener Salt Pellet Fullness Detector. The project leverages an ESP8266 microcontroller in conjunction with an ultrasonic sensor, utilizing ESPHome for easy configuration and management of the device. It's designed to monitor the salt level in a water softener tank and alert when refills are needed.

## Features
- **ESPHome Integration:** Easy configuration and management of the ESP8266 through ESPHome.
- **Ultrasonic Salt Level Monitoring:** Accurate measurement of salt levels using an ultrasonic sensor.
- **Wi-Fi Enabled Notifications:** Alerts sent over Wi-Fi when the salt level is low.
- **Energy Efficient Design:** Optimized for low power consumption, ideal for long-term deployment.
- **Simplified Installation:** User-friendly setup process.

## Hardware Requirements
- ESP8266 Microcontroller
- Ultrasonic Sensor (e.g., HC-SR04)
- Power Supply for ESP8266
- Connecting Wires
- Mounting Hardware for Sensor
<div>
 <img src="/sonic.jpg" alt="Dial 1" title="Dial 1" width="10%"/>
 <img src="/esp.jpg" alt="Dial 1" title="Dial 1" width="10%"/>
</div>

## Software Requirements
- ESPHome
- Arduino IDE (optional for initial flashing)

## Installation and Setup
1. **Assemble the Hardware:** Connect the ultrasonic sensor to the ESP8266 as per the wiring diagram.
2. **Install ESPHome:** Follow the ESPHome installation guide to set up ESPHome on your system.
3. **Configure the Device:** Create a new ESPHome configuration for the ESP8266 and include the necessary configurations for the ultrasonic sensor.
4. **Deploy the Configuration:** Compile and upload the ESPHome configuration to the ESP8266.
5. **Mount the Device:** Securely install the sensor setup in the water softener tank, ensuring the sensor faces the salt pellets.

## Usage
The device will periodically measure the salt level and use your configured ESPHome setup to notify you when it's time to refill the salt.

## Contributing
We welcome contributions! Please review `CONTRIBUTING.md` for guidelines on contributing to this project.

## License
This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgments
- ESPHome community for their invaluable resources.
- Contributors and supporters of the ESP8266 ecosystem.
