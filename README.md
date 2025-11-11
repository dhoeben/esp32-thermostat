
### 🏠 ESP Thermostat (ESPHome + ESP32)
This project is still a work in progress and will serve a **battery powered thermstat** using an **ESP32-H2** and ESPHome over Thread (**Openthred**). So for now, no Matter as this saves battery. __Make sure to have a thread network!__
It uses an E-Ink display and a rotary encoder. It is also created to work together with the OpenTherm Gateway I also created.
The gerber files and PCB schematic are in the .pcb folder. Feel free to use them as you please. I created mine to work with my outlets (Hager Berker R1), but when I have time I will also make a system-55 variant.

### ⬇️ Installation
1) Download latest release
2) Use vscode or flash tool to create firmware 
3) Flash to PCB using USB.
4) Insert 2x CR2450 batteries

### 🚀 Features
- Reads temperature and humidity
- Shows current temperature and humidity
- Shows current state (eco, heating, etc)
- Shows set temperature
- Automatic battery saving and adjustments, they __should__ last about 1.5 - 2 years.

### 🔒 OTA & Maintenance
- Updates can be pushed via Home Assistant or directly through ESPHome over thread
- OTA encrypted and password protected
- Automatic reboot after successful updates
- Safe Mode available if configuration fails to boot