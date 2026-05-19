# Arctic Control v3.5 PRO

Arctic Control is an intelligent automotive thermal management system designed to handle sub-zero temperatures (tested at -35°C in Novosibirsk).

## Features
- **Triple 12V Line Control**: All 3 relays manage 12V high-current zones.
- **Smart Battery Protection**: Carousel logic ensures only one zone is active at a time to prevent battery depletion.
- **Adaptive Auto-Modes**:
  - **Lvl 1 (-5°C)**: Zone 1 active, 10-min battery recovery intervals.
  - **Lvl 2 (-15°C)**: Zone 1 & 2 in rotation, 5-min intervals.
  - **Lvl 3 (-25°C)**: Constant rotation of all 3 zones.
- **External Antenna Support**: Configured for maximum TX Power (+20dBm).
- **Secure Ecosystem**: WPA2 Protected DEV-NET with Captive Portal.

## Installation
### Linux (Arch/Debian)
1. Run `./install.sh`
2. Follow instructions to set password.

### Windows
1. Install Python from `python.org`.
2. Run: `pip install mpremote`
3. Edit `main.py`: Replace `REPLACE_WIFI_PASS` with your password.
4. Run: `mpremote cp main.py :main.py`
5. Run: `mpremote reset`

## License
MIT License.
