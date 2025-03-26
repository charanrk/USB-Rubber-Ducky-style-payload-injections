# Atom Ducky 🦆

## Overview
Atom Ducky is a Rubber Ducky device created using the Atom S3U microcontroller. It provides a powerful HID attack tool with a web-based interface to manage and execute payloads.

## Features
- **Inject Payload:** Load and execute keystroke payloads.
- **Modify Payload:** Edit and update payloads in real time.
- **Live Keyboard:** Emulate keyboard inputs dynamically.
- **Single Payload Execution:** Run single payloads with precision.
- **Templates Manager:** Manage and store multiple payload templates.
- **Rubber Mode:** Enable Rubber Ducky functionality for automated attacks.

## Setting Up Rubber Ducky Mode
1. **Power on the Atom Ducky device.**
2. **Connect to the device's Wi-Fi hotspot:**
   - The default SSID is `Atom Ducky`.
   - Default IP is `10.0.0.15` (in AP mode).
3. **Open the Web Interface:**
   - Go to `http://10.0.0.15` in your browser.
4. **Enable Rubber Mode:**
   - Navigate to the settings page.
   - Toggle the `Rubber Mode` option.
   - Restart the device for changes to take effect.
5. **Upload a Payload:**
   - Use the `Modify Payload` option in the web interface.
   - Write or upload a Rubber Ducky script.
   - Save and inject the payload.
6. **Execute the Payload:**
   - Plug the device into a target system.
   - The payload will execute automatically based on the script.

## Usage
1. Power on Atom Ducky.
2. Connect to the generated Wi-Fi hotspot.
3. Open the web interface via `http://10.0.0.15`.
4. Use the dashboard to manage payloads and settings.

## File Structure
- **index.html** – Web-based interface for Atom Ducky.
- **script.js** – JavaScript functionality for the interface.
- **style.css** – Styling for the web interface.
- **code.py** – Core logic for handling HID attacks and networking.
- **boot.py** – System boot configurations.
- **analyzer.py** – Payload analysis module.
- **buttons.py** – Handles button interactions.
- **colors.py** – RGB LED color management.
- **config_man.py** – Configuration file manager.
- **hid.py** – HID keyboard emulation logic.
- **keycodes.py** – Defines key mappings for execution.
- **networking.py** – Handles web server and AP mode.

## Disclaimer
This tool is intended for educational and authorized security testing purposes only. The developer is not responsible for any misuse or illegal activity.

## Author
Developed by **Charan**.

## License
[MIT License](LICENSE)

