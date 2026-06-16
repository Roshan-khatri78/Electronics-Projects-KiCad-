# KiCad Projects Portfolio
A growing collection of electronics projects designed in KiCad — including schematics, PCB layouts, and Gerber files. Built as part of my hands-on learning journey in electronics engineering and PCB design.

---

## About
These projects range from beginner circuits to progressively complex PCB designs. Each project reflects real learning — including mistakes, revisions, and improvements over time. I add new projects regularly as I continue to grow.

**Skills practiced:**
- Schematic capture & symbol assignment
- PCB layout & trace routing
- Footprint selection & custom footprint creation
- Copper pours, DRC, and design rules
- Gerber file export for fabrication
- 3D model linking & visualization

---

## Projects

### 1. 1-Channel Relay Driver
> `1channelrelay/`

A single-channel relay driver PCB using an NPN transistor (MMBT2222A) to switch a Fujitsu FTR-LYCA005x relay from a microcontroller signal. Includes a flyback diode for back-EMF protection and a decoupling capacitor. All SMD components with a GND copper pour.

**Key components:** MMBT2222A, FTR-LYCA005x relay, 1N4148 flyback diode  
**Concepts:** NPN switching, flyback protection, SMD layout, copper pour

---

### 2. Battery Desulfator Circuit
> `Battery Desulfator circuit/`

An NE555-based pulse generator circuit designed to desulfate lead-acid batteries by sending high-frequency pulses to break down lead sulfate crystals on battery plates. Uses the DISCH pin (pin 7) to drive an IRF244V MOSFET and a flyback inductor (L1).

**Key components:** NE555 timer IC, IRF244V MOSFET  
**Concepts:** 555 astable mode, pulse generation, MOSFET gate drive, battery maintenance circuits

---

### 3. 3V to 40V DC Booster
> `3v to 40v DC booster/`

A DC-DC boost converter PCB that steps up voltage from 3V to up to 40V. Designed for applications requiring higher voltages from low-voltage power supplies.

**Concepts:** Boost converter topology, inductor selection, PCB layout for power electronics

---

### 4. Induction Heater
> `inductionheater/`

An induction heater circuit PCB. Uses high-frequency switching to generate an alternating magnetic field in a work coil, inducing eddy currents in conductive materials to produce heat.

**Concepts:** High-frequency switching, resonant circuits, power PCB layout

---

### 5. 60W SMPS
> `60w smps/`

A 60-watt Switch-Mode Power Supply (SMPS) PCB design. SMPS circuits offer high efficiency compared to linear regulators by using high-frequency switching to regulate output voltage.

**Concepts:** Switching power supply topology, high-frequency PCB layout, power conversion, isolation

---

### 6. Mini Inverter
> `mini inverter/`

A mini inverter circuit using IR2153 gate drive circuitry to convert DC to AC. The IR2153 provides high-side and low-side gate drive signals for a half-bridge or full-bridge MOSFET configuration.

**Key components:** IR2153 gate driver  
**Concepts:** DC-AC inversion, gate drive circuits, half-bridge topology, IR2153 oscillator

---

## Repository Structure
