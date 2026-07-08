# ⚡ KiCad Projects Portfolio

A growing collection of electronics projects designed in **KiCad** — schematics, PCB layouts, and Gerber files. Built as part of my hands-on learning journey in electronics engineering and PCB design.

![KiCad](https://img.shields.io/badge/KiCad-v7%2Fv8-314CB0?style=flat-square)
![Projects](https://img.shields.io/badge/Projects-24-brightgreen?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-blue?style=flat-square)

---

## 📖 About

These projects range from beginner circuits to progressively complex PCB designs. Each one reflects real learning — including mistakes, revisions, and improvements over time. I add new projects regularly as I continue to grow.

**Skills practiced:**
- Schematic capture & symbol assignment
- PCB layout & trace routing
- Footprint selection & custom footprint creation
- Copper pours, DRC, and design rules
- Gerber file export for fabrication
- 3D model linking & visualization
- Hierarchical schematics & multi-sheet designs
- Custom symbol and footprint library creation

---

## 🗂️ Projects

### 1. [1-Channel Relay Driver](./1channelrelay/)
A single-channel relay driver PCB using an NPN transistor (MMBT2222A) to switch a Fujitsu FTR-LYCA005x relay from a microcontroller signal. Includes a flyback diode for back-EMF protection and a decoupling capacitor. All SMD components with a GND copper pour.
- **Key components:** MMBT2222A, FTR-LYCA005x relay, 1N4148 flyback diode
- **Concepts:** NPN switching, flyback protection, SMD layout, copper pour

### 2. [3-Phase BLDC Motor Controller](./3-Phase%20BLDC%20(Brushless%20DC)%20Motor%20Controller/)
A hierarchical, multi-sheet PCB design for driving a 3-phase brushless DC motor, using IR2104 half-bridge gate drivers to switch a 3-phase MOSFET bridge.
- **Key components:** IR2104 gate driver ICs, 3-phase MOSFET bridge
- **Concepts:** Hierarchical schematic design, gate driver circuits, 3-phase commutation, ERC debugging across multiple sheets

### 3. [Battery Desulfator Circuit](./Battery%20Desulfator%20circuit/)
An NE555-based pulse generator circuit designed to desulfate lead-acid batteries by sending high-frequency pulses to break down lead sulfate crystals on battery plates. Uses the DISCH pin (pin 7) to drive an IRF244V MOSFET and a flyback inductor (L1).
- **Key components:** NE555 timer IC, IRF244V MOSFET
- **Concepts:** 555 astable mode, pulse generation, MOSFET gate drive, battery maintenance circuits

### 4. [3V to 40V DC Booster](./3v%20to%2040v%20DC%20booster/)
A DC-DC boost converter PCB that steps up voltage from 3V to up to 40V. Designed for applications requiring higher voltages from low-voltage power supplies.
- **Concepts:** Boost converter topology, inductor selection, PCB layout for power electronics

### 5. [60W SMPS](./60w%20smps/)
A 60-watt Switch-Mode Power Supply (SMPS) PCB design. SMPS circuits offer high efficiency compared to linear regulators by using high-frequency switching to regulate output voltage.
- **Concepts:** Switching power supply topology, high-frequency PCB layout, power conversion, isolation

### 6. [Air Quality Sensor Board](./Air%20Quality%20Sensor%20Board/)
A sensor board PCB for monitoring air quality, pairing an air quality sensor with a microcontroller interface and a Tag-Connect SWD programming footprint for debugging.
- **Key components:** Air quality sensor IC, MCU, Tag-Connect SWD header
- **Concepts:** Analog sensor interfacing, board outline (Edge.Cuts) definition, DRC-clean layout, SWD footprint sourcing

### 7. [Arduino Uno R3 Clone](./Arduino%20R3/)
A faithful clone of the classic Arduino Uno R3, built around the ATmega328P microcontroller, replicating the original reference design.
- **Key components:** ATmega328P (DIP-28), 16MHz crystal, USB-to-serial interface
- **Concepts:** Reference design replication, footprint/symbol matching, copper pour strategy, through-hole MCU layout

### 8. [DC-DC Buck Converter (XL4015 CC/CV)](./DC-DC%20Buck%20converter/)
A step-down converter PCB based on the XL4015 IC, providing constant-current/constant-voltage (CC/CV) regulated output for charging and general power applications.
- **Key components:** XL4015 buck converter IC
- **Concepts:** CC/CV regulation, power inductor selection, feedback loop layout, thermal considerations

### 9. [DS3231 RTC Module](./DS3231%20RTC%20Module/)
A real-time clock breakout board built around the DS3231 high-precision RTC IC with battery backup, for timekeeping in embedded systems.
- **Key components:** DS3231 RTC IC, coin cell battery backup
- **Concepts:** RTC interfacing over I2C, battery backup circuit design, breakout board layout

### 10. [HC-06 Bluetooth Module](./HC-06%20BLUETOOTH%C2%AE%20Module/)
A breakout/reference design board for the HC-06 Bluetooth serial module, enabling wireless UART communication for microcontroller projects.
- **Key components:** HC-06 Bluetooth serial module
- **Concepts:** Module-level symbol/footprint sourcing, wireless UART bridging, breakout board design

### 11. [Induction Heater](./inductionheater/)
An induction heater circuit PCB. Uses high-frequency switching to generate an alternating magnetic field in a work coil, inducing eddy currents in conductive materials to produce heat.
- **Concepts:** High-frequency switching, resonant circuits, power PCB layout

### 12. [Mini Inverter](./mini%20inverter/)
A mini inverter circuit using IR2153 gate drive circuitry to convert DC to AC. The IR2153 provides high-side and low-side gate drive signals for a half-bridge MOSFET configuration.
- **Key components:** IR2153 gate driver
- **Concepts:** DC-AC inversion, gate drive circuits, half-bridge topology, IR2153 oscillator

### 13. [L298 Motor Driver](./L298%20motor%20driver/)
A motor driver PCB based on the L298N dual H-bridge IC, capable of driving two DC motors or one stepper motor with direction and speed control. Designed with onboard power regulation and protection diodes.
- **Key components:** L298N dual H-bridge IC
- **Concepts:** H-bridge motor control, dual DC/stepper motor drive, flyback diode protection, PCB layout for moderate current loads

### 14. [LED Flasher](./LED%20flasher/)
A simple astable multivibrator LED flasher circuit. A foundational circuit demonstrating oscillator design and timing with discrete components or a 555 timer.
- **Concepts:** Astable oscillator, RC timing, LED drive, beginner PCB layout

### 15. [SPO2 (Pulse Oximeter)](./SPO2/)
A pulse oximeter circuit PCB for measuring blood oxygen saturation (SpO2) and heart rate. Uses IR and red LEDs with a photodetector to sense light absorption differences in oxygenated vs. deoxygenated blood.
- **Concepts:** Optical sensing, analog signal conditioning, biopotential measurement, photodetector interfacing

### 16. [STM32 DEV Board](./STM32%20DEV%20board/)
A custom development board PCB for the STM32 microcontroller family. Includes necessary support circuitry such as decoupling capacitors, reset circuitry, boot mode selection, and programming headers.
- **Key components:** STM32 microcontroller
- **Concepts:** Microcontroller PCB design, power decoupling, SWD/JTAG programming interface, crystal oscillator layout

### 17. [USB to UART Converter](./USB2UART/)
A USB-to-UART bridge PCB for serial communication between a PC and embedded systems. Used for programming and debugging microcontrollers that lack native USB support.
- **Key components:** USB-UART bridge IC (e.g. CH340/CP2102)
- **Concepts:** USB full-speed interface, UART protocol, level shifting, USB connector footprint, ESD protection

### 18. [ESP32 Demo Project](./esp32%20demo%20project/)
A demonstration PCB built around the ESP32 module, exploring its GPIO, power, and communication capabilities. Serves as a base reference design for ESP32-based projects.
- **Key components:** ESP32 module
- **Concepts:** ESP32 power requirements, decoupling, RF layout considerations, boot mode strapping pins

### 19. [ESP32 Drone (Flight Controller)](./esp32Drone/)
An ESP32-based quadcopter flight controller PCB. Integrates IMU sensing, ESC signal output, power distribution, and communication interfaces in a compact layout suitable for a drone frame.
- **Key components:** ESP32, IMU (e.g. MPU-6050/ICM-42688), USB-C
- **Concepts:** Flight controller architecture, IMU interfacing, PWM/DSHOT ESC output, hierarchical schematics, 4-layer PCB layout, USB-C power delivery

### 20. [Microcontroller-Controlled Digital Radio Receiver](./microcontroller-controlled%20digital%20radio%20receiver/)
A digital radio receiver PCB controlled by a microcontroller, enabling tuning and control of FM/AM radio stations via software. Combines RF front-end with digital control logic.
- **Key components:** Radio receiver IC, microcontroller
- **Concepts:** RF signal reception, I2C/SPI control interface, audio output, antenna design considerations

### 21. [One Digit Up/Down Counter](./one%20digit%20updown%20counter/)
A single-digit up/down counter circuit with a 7-segment display, driven by logic ICs or a microcontroller. Counts up or down based on input signals.
- **Key components:** Up/down counter IC, 7-segment display
- **Concepts:** Digital counting logic, BCD to 7-segment decoding, push-button debouncing, display drive

### 22. [Portable FM Radio Receiver](./portable%20FM%20radio%20receiver/)
A portable FM radio receiver PCB using a dedicated FM receiver IC, designed for battery-powered operation. Includes audio output and tuning interface in a compact layout.
- **Key components:** FM receiver IC (M6955), Arduino Pro Mini
- **Concepts:** FM demodulation, audio amplification, hierarchical schematic design, compact 4-layer PCB layout, custom symbol creation

### 23. [ESP32 Oscilloscope & Function Generator](./ESP32_OSCILLOSCOPE_AND_FN_GENERATOR/) 🎓 *Final Year Project*
An ESP32-based oscilloscope and function generator PCB for the BEICE final year project (FYP). Combines signal acquisition (oscilloscope) and signal synthesis (function generator) in a single instrument platform.
- **Key components:** ESP32, ADC/DAC circuitry, op-amps
- **Concepts:** High-speed signal sampling, DAC waveform generation, analog front-end design, instrument PCB layout, hierarchical schematics

### 24. [Analog Soldering Station Kit](./analog%20soldering%20station%20kit/)
An analog temperature-controlled soldering station PCB. Uses feedback from the soldering iron's thermocouple or temperature sensor to regulate tip temperature via PWM power control.
- **Key components:** TL494 PWM controller, LM358 op-amp
- **Concepts:** Closed-loop temperature control, PWM power regulation, thermocouple signal conditioning, analog feedback design

---

## 📁 Repository Structure

```
Electronics-Projects-KiCad-/
├── 1channelrelay/
├── 3-Phase BLDC (Brushless DC) Motor Controller/
├── 3v to 40v DC booster/
├── 60w smps/
├── Air Quality Sensor Board/
├── analog soldering station kit/
├── Arduino R3/
├── Battery Desulfator circuit/
├── DC-DC Buck converter/
├── DS3231 RTC Module/
├── esp32 demo project/
├── esp32Drone/
├── ESP32_OSCILLOSCOPE_AND_FN_GENERATOR/
├── HC-06 BLUETOOTH® Module/
├── inductionheater/
├── L298 motor driver/
├── LED flasher/
├── microcontroller-controlled digital radio receiver/
├── mini inverter/
├── one digit updown counter/
├── portable FM radio receiver/
├── SPO2/
├── STM32 DEV board/
├── USB2UART/
├── .gitignore
└── README.md
```

Each project folder contains:
```
<project-name>/
├── *.kicad_sch      # Schematic files
├── *.kicad_pcb      # PCB layout files
└── Gerber/          # Fabrication-ready Gerber exports
```

---

## 🛠️ Tools Used

- **KiCad EDA** (v7/v8)
- Manufacturer datasheets for component selection
- KiCad 3D viewer for visual inspection
- Custom symbol & footprint libraries

---

## 📝 Note on Quality

These projects document my learning process openly. Some designs may have imperfections or areas for improvement — that's intentional. I revisit and improve designs as my knowledge grows rather than hiding earlier work.

---

## 📄 License

Unless otherwise stated, all projects in this repository are shared for educational and portfolio purposes.

Feel free to open an issue or start a discussion if you have suggestions or feedback.
