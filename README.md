<h1>Compiled for Momentum-Firmware</h1>
<div align="center">
  <img src="https://avatars.githubusercontent.com/u/176677387" width="150" height="auto" />
  <h1> 🌟 FZ nRF24 Jammer 🌟 </h1>
</div>

## Credits to W0rthlessS0ul
Ref to original post:  **[here](https://github.com/W0rthlessS0ul/FZ_nRF24_jammer)**

# DISCLAIMER:

This repository contains software that may interfere with radio connections.

Attention: The deliberate jamming of radio connections might be illegal in your country and in many other countries. This tool is provided for research and experimental purposes only. Using it in practice is prohibited unless expressly authorised by the relevant authorities.

The developer assumes no liability for any damages or legal consequences arising from the use of this software.

## ✨ Newly Added Features (2025)

- **Nightfall's Options Submenu:**
  - Custom jamming profiles: PS4, PS5, Xbox, Switch, Wireless Audio, AirPods/Pro.
  - BLE-based devices (PS4, PS5, AirPods/Pro) use BLE jamming logic (channels 2, 26, 80).
  - Proprietary devices (Xbox, Switch, Wireless Audio) use constant carrier jamming on their respective channels.

- **WiFi Jammer Optimized for EU/DE:**
  - Optimized for European WiFi (channels 1–13, 2.4 GHz).
  - "All Channels" jams the entire 2.4 GHz band (RF_CH 1–83) for maximum effect.
  - "Single Channel" jams ±10 RF_CH around the selected channel for strong, focused jamming.
  - All WiFi networks (WPA2, WPA3, WPS, etc.) are jammed identically (encryption does not matter for jamming!).

- **Improved Menu Navigation:**
  - Submenus and jamming screens are now robust: BACK always exits, no more getting stuck.
  - Nightfall menu bug fixed (no more double rendering).

- **General Stability:**
  - Code cleanup, bugfixes, and improved error handling.
  - More responsive UI and key handling.

---
![Screenshot 2025-06-19 021311](https://github.com/user-attachments/assets/e08dde06-e35f-4ce2-85f6-1e9157ecde51)

## Usage Notes
- The jammer only affects 2.4 GHz WiFi (not 5 GHz).
- Encryption (WPA2, WPA3, WPS) does not protect against jamming.
- Use responsibly and only in authorized environments.

---
