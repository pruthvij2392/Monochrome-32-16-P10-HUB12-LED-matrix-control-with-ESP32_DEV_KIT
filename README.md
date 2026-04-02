# Monochrome-32-16-P10-HUB12-LED-matrix-control-with-ESP32_DEV_KIT
ESP32-based scrolling text display using 6 P10 (32x16) LED panels connected via HUB12. Achieves 96x32 resolution with smooth animation using DMD32Plus and timer interrupt for flicker-free performance.

📖 Description

This project demonstrates a scrolling text display using an ESP32 and multiple P10 (32x16) LED matrix panels connected in series. The system uses the DMD32Plus library to control the panels and display smooth horizontal scrolling text.

A total resolution of 96x32 pixels is achieved by chaining 6 panels (3 across × 2 down). The ESP32 handles display refresh using a hardware timer interrupt for stable and flicker-free output.
============================================================
🧰 Hardware Used
ESP32 Dev Kit
6 × P10 LED Matrix Panels (32x16 each)
HUB12 Connectors
Jumper Wires
Power Supply (5V, sufficient current for panels)
============================================================
🔌 Panel Configuration
Panel Size: 32 × 16 pixels
Total Panels: 6
Arrangement: 3 (horizontal) × 2 (vertical)
Final Resolution: 96 × 32 pixels
============================================================
⚙️ Features
Smooth horizontal scrolling text
Timer interrupt-based display refresh
Large font rendering using Arial Black 16
Multi-panel cascading support
Flicker-free display using SPI scanning
============================================================
💻 Libraries Used
DMD32Plus
SystemFont5x7
Arial_Black_16
=============================================================
🚀 How It Works
ESP32 initializes the LED panels using SPI communication.
A hardware timer continuously refreshes the display.
Text is drawn and moved pixel-by-pixel across the screen.
The display scrolls from right to left continuously.

==============================================================
📷 Output
Scrolling text like:
"HEY PRUTHVI.." across the 96x32 LED display.
