
# Tamacatchi

A Tamagotchi-inspired project made by me :).

This project is my first attempt at designing a complete project in KiCad, including the schematic and PCB design, it has:

- Screen for displaying information
- Three switches for user input
- Buzzer for sound feedback
- RTC (Real-Time Clock)
- Temperature and humidity sensor

## Hardware Design

### 3D Model

A 3D representation of the project designed in KiCad.

![Tamacatchi 3D Model](https://github.com/user-attachments/assets/505e394e-79b2-4d65-a91b-9c8e746e6867)

### Schematic

The schematic showing the circuit and component connections.

![Tamacatchi Schematic](https://github.com/user-attachments/assets/51af7d64-97af-4540-b0e3-fe379faba95f)

## Code

The code was updated to support the additional components introduced in the tutorial, including the rtc and the buzzer.

## Controls

- **Button 1 (D2):** Opens the radial menu or confirms a selection.
- **Button 2 (D3):** Switches between the pet view and stats view.
- **MPU6050:** Tilt the device to navigate the menu, or shake it to make the pet react and change stats.

**Menu actions:**
- **Up:** Nap
- **Right:** Play
- **Down:** Feed
- **Left:** Pet

## About the Project

This is my first time creating a complete project in KiCad, making it a learning experience, i would bet that the copper lines could be better optimized since i only put some in the background.

