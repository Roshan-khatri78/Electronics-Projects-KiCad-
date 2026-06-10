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

An NE555-based pulse generator circuit designed to desulfate lead-acid batteries by sending high-frequency pulses to break down lead sulfate crystals on battery plates.

**Key components:** NE555 timer IC  
**Concepts:** 555 astable mode, pulse generation, battery maintenance circuits

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

## Repository Structure

```
Electronics-Projects-KiCad-/
├── 1channelrelay/
│   ├── *.kicad_sch
│   ├── *.kicad_pcb
│   └── Gerber/
├── Battery Desulfator circuit/
│   ├── *.kicad_sch
│   ├── *.kicad_pcb
│   └── Gerber/
├── 3v to 40v DC booster/
│   ├── *.kicad_sch
│   ├── *.kicad_pcb
│   └── Gerber/
├── inductionheater/
│   ├── *.kicad_sch
│   ├── *.kicad_pcb
│   └── Gerber/
└── README.md
```

---

## Tools Used

- [KiCad EDA](https://www.kicad.org/) (v7/v8)
- Manufacturer datasheets for component selection
- KiCad 3D viewer for visual inspection

---

## Note on Quality

These projects document my learning process openly. Some designs may have imperfections or areas for improvement — that's intentional. I revisit and improve designs as my knowledge grows rather than hiding earlier work.

---

## License

Unless otherwise stated, all projects in this repository are shared for educational and portfolio purposes.  
Feel free to open an issue or start a discussion if you have suggestions or feedback.
