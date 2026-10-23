# Tamacatchi

Tamacatchi is a small virtual pet inspired by the original Tamagotchi, a handheld digital pet that you take care of by feeding it, playing with it and letting it rest. The idea behind this project is to create a physical device where you can interact with your pet using buttons and movement controls.

The device includes a screen to display the pet and its stats, a buzzer for sound feedback, an RTC to keep track of time, and a temperature and humidity sensor. It also uses an MPU6050, which lets you tilt the device to navigate the menu or shake it to make the pet react and change its stats. This is my first attempt at designing a complete project in KiCad, including both the schematic and PCB layout, so it has been a great learning experience.

## Hardware Design

### 3D Model

A 3D representation of the project designed in KiCad.

![Tamacatchi 3D Model](https://github.com/user-attachments/assets/505e394e-79b2-4d65-a91b-9c8e746e6867)

### Schematic

The schematic showing the circuit and component connections.

![Tamacatchi Schematic](https://github.com/user-attachments/assets/51af7d64-97af-4540-b0e3-fe379faba95f)

## Code

The code was updated to support the additional components introduced in the tutorial, including the RTC and the buzzer.

## Controls

- **Button 1 (D2):** Opens the radial menu or confirms a selection.
- **Button 2 (D3):** Switches between the pet view and stats view.
- **MPU6050:** Tilt the device to navigate the menu, or shake it to make the pet react and change stats.

### Menu Actions

- **Up:** Nap
- **Right:** Play
- **Down:** Feed
- **Left:** Pet

## About the Project

This is my first time designing a complete PCB in KiCad, from the schematic to the PCB layout. I still have things I would like to improve, especially the copper routing, since I mainly focused on getting everything connected rather than optimizing the layout. Overall, this project has helped me learn more about electronics, circuit design and PCB development, and I hope to improve it further in the future.

