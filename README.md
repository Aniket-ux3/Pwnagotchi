# Pwnagotchi

This project documents my customized [Pwnagotchi](https://pwnagotchi.ai) setup using a Raspberry Pi Zero W, a Waveshare V4 2.71" E-Ink display, and a custom-trained deep learning model in place of the default A2C agent. The goal is to create a portable, AI-powered passive Wi-Fi handshake collector for WPA/WPA2 networks.

## Project Overview
 <!-- Optional: replace with your own image path -->

- **Device**: Raspberry Pi Zero W
- **Display**: Waveshare V4 2.71" E-Ink
- **Storage**: 64GB microSD card
- **Power Source**: Portable USB Power Bank
- **Image Used**: `pwnagotchi-2.8.9-32bit.img`
- **AI Agent**: Custom Deep Learning Agent (replaces default A2C)

---

##  Features

-  **Deep Learning Agent**: Replaces the default A2C agent with a TensorFlow Lite (TFLite) model for more adaptive behavior.
-  **Passive Wi-Fi Handshake Collection**: Listens for WPA/WPA2 handshakes in the background while maintaining a low power footprint.
-  **Fully Portable**: Runs entirely from a battery pack, perfect for wardriving or long-range sniffing sessions.
-  **E-Ink Display Output**: Minimal power usage with clean status updates via a 2.71" E-Ink display.
-  **64GB Storage**: Ample space for handshake captures, logs, and agent training data.

---

##  Hardware Requirements

| Component           | Description                       |
|---------------------|-----------------------------------|
| Raspberry Pi Zero W | Low-power single-board computer   |
| Waveshare 2.71" V4  | E-Ink display (version 4)         |
| 64GB microSD Card   | With Pwnagotchi image installed   |
| Power Bank          | Portable power source             |
| USB OTG Cable       | (Optional) for debugging           |

---
# Example tool: Raspberry Pi Imager or Etcher
[`pwnagotchi-2.8.9-32bit.img`](https://github.com/jayofelony/pwnagotchi/releases/tag/v2.8.9)

Happy hacking!
Image Credits: jayofelony

