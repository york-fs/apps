# Accelerator Pedal Position Sensor (APPS)

A custom accelerator pedal position sensor built around an STM32F103 MCU for drive-by-wire and EV applications.  
This module measures pedal position using two SS49E Hall-effect sensors with independent, opposed magnets, provides a digital brake signal, and communicates throttle data directly to the inverter over CAN bus.

## Features
- **MCU**: STM32F103
- **Position sensing**:  
  - Two SS49E Hall-effect sensors  
  - Independent, opposed magnet configuration for rule compliance and redundancy 
- **Brake output**: Digital output line for brake LED / ECU input  
- **User controls**:  
  - Reset button  
  - Calibration button (pedal travel limits)
- **CAN transceiver**:  
  - Throttle data transmission  
  - Ready-to-drive state reporting  
  - Calibration / curve configuration

<img width="1746" height="778" alt="image" src="https://github.com/user-attachments/assets/5c9d4c15-da50-49dc-af65-d7dec6a074a9" />
