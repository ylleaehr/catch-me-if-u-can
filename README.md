# “Catch Me If You Can” – ESP32 Retro Chase Game

## Project Overview
“Catch Me If You Can” is a self-built 2D chase game inspired by the playground game “Fangis.” The system is implemented on an ESP32 microcontroller using MicroPython and displayed on an 8×8 NeoPixel LED matrix. Players control their character using a joystick and dual-button module. The device is fully portable thanks to a 3.7V Li-Ion battery and a 3D-printed enclosure.

## Game Play
Gameplay
The game features a top-down 8×8 arena where two opponents take different roles:
- Hunter (Fänger) tries to catch the opponent
- Runner (Wegrenner) tries to escape until the timer expires

Movement is pixel-based and controlled with the joystick. Random obstacles add strategic elements, while special abilities enhance gameplay.

## Hardware Components
- ESP32 Dev Board (MicroPython)
- NeoPixel 8×8 Matrix for the main game display for status and messages
- Joystick A06-05 TZT for directional control
- M5Stack Dual-Button Unit for abilities
- DFPlayer Mini + speaker for sound effects
- 3.7V Li-Ion 500mAh battery for mobile power
- Custom 3D-printed PLA enclosure

Multiplayer functionality is supported via ESP-NOW wireless communication.

