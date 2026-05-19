# ArcticControl v3.3 🧊🚗

High-performance automotive heating management system designed for extreme winter conditions (tested in Novosibirsk, -35°C). Powered by Seeed Studio XIAO ESP32-C3.

## 🚀 Key Features
- *Smart Carousel Logic*: Rotates 3 heating zones every 5 minutes to prevent battery drain.
- *Adaptive Temperature Levels*:
  - *Lvl 1 (-5°C)*: 1 zone active (33% duty cycle).
  - *Lvl 2 (-15°C)*: 2 zones active (66% duty cycle).
  - *Lvl 3 (-25°C)*: 3 zones active (100% duty cycle).
- *Captive Portal UI*: Automatic dashboard pop-up on connection.
- *Extreme Range*: Optimized for external antenna with +20dBm TX power.
- *Secure Ecosystem*: WPA2 protected Wi-Fi network (DEV-NET).

## 🛠 Hardware Required
- *Controller*: Seeed Studio XIAO ESP32-C3.
- *Sensor*: DS18B20 (Waterproof version).
- *Relays*: 3-Channel 3.3V Relay Module.
- *Power*: DC-DC Step-down (12V to 5V).
- *Antenna*: 2.4GHz External Antenna.

## 💻 Installation (Arch Linux)
1. *Connect XIAO* to your USB port.
2. *Install tools*:
   