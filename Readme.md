# Smart Helmet for Coal Miners

## Overview
This project is a **Smart Helmet for Coal Miners** that ensures miner safety using IoT-based technology. It includes various sensors for detecting environmental hazards, an emergency alert system, and wireless data transmission.

## Features
- **Temperature Monitoring:** Uses DHT11 sensor to measure real-time temperature.
- **Gas Detection:** MQ-02 sensor detects hazardous gases.
- **Helmet Detection:** IR sensor ensures the helmet is worn.
- **Obstacle Detection:** IR sensor alerts about obstacles.
- **Emergency SOS Button:** Sends an emergency signal.
- **Wireless Communication:** RF modules transmit data to a monitoring system.
- **Buzzer Alert:** Triggers an alarm for safety warnings.

## Components Used
| Component | Purpose |
|-----------|---------|
| **Arduino Uno** | Microcontroller |
| **DHT11** | Temperature Sensor |
| **MQ-02** | Gas Detection |
| **IR Sensor 1** | Helmet Detection |
| **IR Sensor 2** | Obstacle Detection |
| **RF Transmitter** | Sends data |
| **RF Receiver** | Receives data |
| **Buzzer** | Alerts user |
| **SOS Button** | Emergency alert |

## Circuit Diagram
The following diagram represents the pin connections:

| **Component** | **Arduino Uno Pin** |
|--------------|------------------|
| **DHT11** | VCC → 5V, GND → GND, Data → Digital Pin 2 |
| **MQ-02** | VCC → 5V, GND → GND, A0 → Analog Pin A0 |
| **IR Sensor (Helmet)** | VCC → 5V, GND → GND, OUT → Digital Pin 3 |
| **IR Sensor (Obstacle)** | VCC → 5V, GND → GND, OUT → Digital Pin 4 |
| **RF Transmitter** | VCC → 5V, GND → GND, Data → Digital Pin 5 |
| **RF Receiver** | VCC → 5V, GND → GND, Data → Digital Pin 6 |
| **Buzzer** | Positive → Digital Pin 7, Negative → GND |
| **SOS Button** | One side → GND, Other side → Digital Pin 8 |



## Installation & Usage
1. Connect all components to the Arduino Uno as per the circuit diagram.
2. Upload the **Transmitter.ino** and **Receiver_part.ino** codes to the respective Arduino boards.
3. Open the Serial Monitor to view sensor readings and alerts.
4. Press the **SOS button** in case of an emergency.

## Technologies Used
- **IoT, Embedded Systems**
- **Wireless Communication (RF Modules)**
- **Sensors (DHT11, MQ-02, IR)**

## Contributing
Feel free to fork this project and contribute by improving the design or adding new features.

## License
This project is open-source under the MIT License.
