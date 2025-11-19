# TE2004B_EmbeddedSystems_PCB

This repository contains custom KiCad libraries for embedded systems PCB design, including symbol libraries and footprint libraries for ESP32-C3 SuperMini, STM32 Nucleo-F767ZI, and various sensors and components.

## Project Structure

- **PCBEmbebidosLibSymbol/** - Custom symbol library folder
  - `ESP32-C3_SUPERMINI_TH.kicad_sym` - ESP32-C3 SuperMini symbols
  - `NUCLEO-F767ZI.kicad_sym` - STM32 Nucleo-F767ZI symbols

- **PCBEmebebidosLibFootPrint.pretty/** - Custom footprint library folder
  - Contains footprints for battery, ESC, MCP2515, ESP32-C3, motor encoder, MPU9250, regulators, servo, STM32, and TJA1051

## How to Import Libraries into KiCad

### Importing Symbol Libraries

1. Open KiCad and go to **Preferences** → **Manage Symbol Libraries...**

2. In the Symbol Libraries dialog, click on the **Project Specific Libraries** tab (if you want the library only for this project) or **Global Libraries** tab (if you want it available for all projects)

3. Click the **folder icon** (Browse Libraries) at the bottom of the window

4. Navigate to the `PCBEmbebidosLibSymbol` folder in this repository

5. Select the symbol files you want to add:
   - `ESP32-C3_SUPERMINI_TH.kicad_sym`
   - `NUCLEO-F767ZI.kicad_sym`

6. Click **Open** and then **OK**

### Importing Footprint Libraries

1. Open KiCad and go to **Preferences** → **Manage Footprint Libraries...**

2. In the Footprint Libraries dialog, click on the **Project Specific Libraries** tab (if you want the library only for this project) or **Global Libraries** tab (if you want it available for all projects)

3. Click the **+** icon at the bottom to add a new library entry

## Available Components

### Symbols
- ESP32-C3 SuperMini (Through-Hole)
- STM32 Nucleo-F767ZI

### Footprints
- Battery connector
- ESC (Electronic Speed Controller)
- MCP2515 CAN controller
- ESP32-C3 SuperMini module
- Motor with encoder
- MPU9250 IMU sensor
- Voltage regulator
- Servo motor connector
- STM32 Nucleo-F767ZI
- TJA1051 CAN transceiver



