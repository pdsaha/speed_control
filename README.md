## Fan Speed Control Using Temperature and Humidity Sensor

This project implements an intelligent, automated fan speed control system based on environmental temperature and humidity readings. Built using an Arduino Uno and a DHT22 sensor, the system dynamically adjusts fan speed to maintain a comfortable room environment, optimizing energy usage and enhancing user convenience.

### 🚀 Project Overview

The system reads real-time temperature and humidity using the DHT22 sensor. Users can define a temperature range via a keypad. The Arduino microcontroller compares the current readings with the user-defined thresholds and controls a fan and heater accordingly:

* If temperature is **below** the minimum threshold: the **heater** is turned on.
* If temperature is **above** the maximum threshold: the **fan** is activated.
* The **fan speed** increases proportionally with the temperature difference using a PWM signal.
* If the temperature lies within the set range, **all devices are turned off**, maintaining equilibrium.

### 🔧 Key Components

* Arduino Uno
* DHT22 Temperature & Humidity Sensor
* MOSFET (IRFZ44N), BJT (BC589)
* 3x4 Keypad and 16x4 LCD Display
* Hall effect sensor (for RPM feedback)
* PWM-based fan control
* Power supply and breadboard circuitry

### 🧠 Features

* Automatic real-time control of fan speed based on sensor data
* PWM for smooth speed control
* Energy-efficient and low power consumption
* Real-time LCD display for temp, humidity, fan speed, and set thresholds
* Ideal for smart homes, elderly care, and energy-conscious environments
