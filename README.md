# Soil-Moisture-Monitor
wokwi file-https://wokwi.com/projects/459891055074291713
Realtime Soil Moisture Monitoring Dashboard
Project Overview
An end-to-end IoT system that reads soil moisture data using a sensor (simulated via potentiometer on Wokwi), syncs data to Firebase Realtime Database, and displays real-time updates on a Node-RED web dashboard with a below-20% alert system.
Simulation: Wokwi Project

System Architecture
Potentiometer (simulates sensor)
        ↓
    ESP32 (GPIO34)
        ↓
 Firebase Realtime Database
        ↓
  Node-RED Dashboard
  (Gauge + Chart + Alert)
