# Altimeter_Log
Rocket Altimeter and Log

This project is designed for a rocket altimeter logging system using a Dps310 pressure sensor, an ESP32 microcontroller, and a WiFi access point. The system logs pressure measurements during flight and provides real-time data access via a web server.

Features:
-Measures and logs pressure data during flight.
-Implements an automatic overwriting system to prevent data loss when RAM is maxed out.
-Filters out insignificant pressure changes to optimize storage.
-Hosts a web server for real-time data access.
-Implements a WiFi access point for easy connectivity.

Components Used:
-ESP32 (or any compatible microcontroller with WiFi capabilities)
-Dps310 Pressure Sensor
-Arduino IDE (or PlatformIO for development)

Dependencies:
-Dps310.h
-WiFi.h
-NetworkClient.h
-WiFiAP.h

