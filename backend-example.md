# Smart Waste Monitoring System

An IoT-driven solution for real-time monitoring and management of waste container fill levels, powered by ultrasonic sensors, ESP32, LoRa/MQTT, and ASP.NET Core.

---

## 🚀 Features

- **Real-Time Monitoring**: Ultrasonic sensors on ESP32 publish fill-level data via LoRa/MQTT.  
- **Backend API**: Built with ASP.NET Core (C#) and PostgreSQL for data storage and processing.  
- **Web Dashboard**: Interactive map view (Google Maps/Leaflet) showing container locations and statuses.  
- **Alerts & Notifications**: Push and in-app alerts when fill level exceeds configurable thresholds.  
- **Predictive Forecasting**: Simple regression model forecasts fill levels 1–2 days ahead.  
- **Role-Based Access**: Administrator, Dispatcher, Driver, and Engineer roles with custom permissions.  
- **Offline Resilience**: Solar-powered battery backup ensures sensor uptime in all conditions.

---

## 📦 Architecture Overview

[Ultrasonic Sensor] --> [ESP32] --> LoRa/MQTT --> [MQTT Broker]
--> [ASP.NET Core API] --> [PostgreSQL]
|
v
[Web Dashboard]

---

## 🛠️ Getting Started

### Prerequisites

- .NET 6 SDK or later  
- PostgreSQL 12+ database  
- MQTT Broker (e.g., Mosquitto)  
- Node.js (for front-end dependencies)  

### Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-org/smart-waste-monitoring-system.git
   cd smart-waste-monitoring-system
