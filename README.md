# Smart-Plant-Care-System
The Smart Plant Care System is an IoT-based solution designed to automatically monitor and maintain the health of plants by measuring key environmental parameters such as soil moisture, temperature, and humidity. Using an ESP32 microcontroller, the system automates irrigation and provides real-time data visualization on cloud platforms like ThingSpeak or Blynk.

# Features

Automatic Watering: Waters the plant automatically when soil moisture drops below the threshold.

Real-time Monitoring: Tracks soil moisture, temperature, and humidity continuously.

IoT Integration: Sends sensor data to the cloud for remote access and analytics.

Alert System: Notifies users when environmental conditions become unfavorable.

Energy-efficient Operation: Uses minimal power and optimizes pump operation.

Dashboard Access: Displays live plant health data on a mobile or web dashboard.

# Project Overview

The system uses ESP32 as the control unit, interfaced with DHT11/DHT22 for temperature and humidity sensing, and a soil moisture sensor to detect water levels in the soil. When the soil is dry, a relay-controlled water pump is activated automatically to irrigate the plant. All sensor data is uploaded to a cloud service for live tracking and analysis.

# Components Used

ESP32 - Wi-Fi enabled microcontroller for processing and IoT communication
Soil Moisture Sensor - Measures the water content in soil
DHT11 / DHT22 Sensor - Measures temperature and humidity
Relay Module - Controls water pump or solenoid valve
Mini Water Pump - Pumps water to the plant automatically
Jumper Wires & Breadboard - Circuit connections
Power Supply (5V) - Powering the ESP32 and peripherals

# Working Principle

The soil moisture sensor measures the current moisture level of the soil.

If the moisture level falls below a set threshold, the relay activates the pump to water the plant.

DHT11/DHT22 continuously monitors the surrounding temperature and humidity.

The ESP32 sends all readings to the cloud (ThingSpeak / Blynk / Firebase) via Wi-Fi.

The user can view real-time data and graphs on a dashboard or mobile app.

The system automatically turns off the pump when optimal soil moisture is reached.
Software and Tools

Arduino IDE / PlatformIO

ThingSpeak / Blynk / Firebase

ESP32 Board Package

Wi-Fi Network

# Applications

Smart irrigation systems

Indoor plant monitoring

Greenhouse automation

Agricultural water management

IoT-based farming systems

# Future Enhancements

Integration with mobile alerts (SMS / WhatsApp / Telegram)

Solar power integration for sustainable energy use

Addition of light sensors for sunlight monitoring

AI/ML-based prediction for optimal watering cycles

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/6633281c-f2d4-4dba-a0bb-823c8cd155a5" />
