# Smart Plant Watering System

## Introduction

Plants play a vital role in creating oxygen and purifying the air, contributing to a healthy environment. However, urbanization and lack of space have led many to grow plants in pots on windowsills, requiring consistent watering and sunlight. Busy schedules often lead to neglect, causing plants to suffer. This project aims to address this issue by creating a smart plant watering system that ensures plants are watered adequately, reducing labor and water wastage, and promoting sustainability.

## Proposed Solution

The smart plant watering system measures soil moisture, temperature, and humidity to determine when to water plants. This system maximizes plant nutrition, reduces labor and danger, minimizes water wastage, and helps save on water bills.

## Project Scenario

This system is primarily intended for indoor plants, using a wireless sensor network implemented with an Arduino Uno and four sensors. The sensors monitor soil moisture, temperature, humidity, and water levels, automatically watering the plants as needed. Notifications are sent to users when water levels are low, ensuring consistent care for plants.

## Design and Implementation

### Components Used

1. **Arduino Uno**: A microcontroller board with 6 analog inputs, 14 digital input/output pins, USB connection, power jack, and reset button.
2. **LCD Character Display**: A 16x2 display used to show system status and sensor readings.
3. **Soil Moisture Sensor**: Measures soil moisture levels to determine when the plant needs watering.
4. **Ultrasonic Sensor (HC-SR04)**: Measures water level in the bucket to ensure adequate water supply.
5. **DHT11 Sensor**: Measures temperature and humidity to monitor environmental conditions.
6. **Relay Module**: Electrically activated switch to control the water pump.
7. **Water Pump**: Pumps water to the plants when needed.
8. **GSM Module**: Sends SMS notifications to the user when water levels are low.

### System Operation

1. The soil moisture sensor checks if the plant needs water.
2. If watering is needed, the ultrasonic sensor checks the water level in the bucket.
3. If the water level is low, the system alerts the user via LED, piezo speaker, and SMS.
4. If the water level is sufficient, the system waters the plant for 3 seconds at a time until the soil moisture is adequate.
5. Notifications are displayed on the LCD, and the piezo speaker alerts the user when watering is complete.

### Power Supply

The system is designed for indoor use, powered by USB or a power bank, lasting 3-5 days.

## Instructions to Follow the Steps

To see the steps on how this project is created, please follow the instructions in this README file.

## Setup and Installation

1. **Install Arduino IDE**: Download and install the Arduino IDE from the [official website](https://www.arduino.cc/en/software).
2. **Connect Components**: Connect the Arduino Uno, sensors, relay module, water pump, LCD, and GSM module as per the wiring diagram.
3. **Upload Code**: Write the Arduino code to read sensor data and control the water pump. Upload the code to the Arduino Uno using the Arduino IDE.
4. **Calibrate Sensors**: Adjust the thresholds for soil moisture and water level based on the specific needs of your plants.
5. **Power the System**: Connect the Arduino Uno to a power source (USB or power bank).

## Usage

1. **Fill Water Tank**: Ensure the water tank is filled to the required level.
2. **Monitor System**: Check the LCD for sensor readings and system status.
3. **Notifications**: Respond to SMS notifications and alerts from the system.

## Conclusion

This smart plant watering system ensures plants receive adequate water, promoting sustainability and reducing labor. By following this README file, you can set up and implement the system to maintain healthy indoor plants.

## For Deatailed Information
Follow the Smart Plant watering Guidlines which has also the code for teh project
For detailed results, you can download and view the [Result.mp4](https://github.com/Senedaa/Smart-Plant-Watering-System/raw/main/Result.mp4) file directly.

