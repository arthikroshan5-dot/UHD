# Universal Hacking Tool (UHT)

![Universal Hacking Tool project design](../images/uht-concept.png)

## Project Overview

The **Universal Hacking Tool (UHT)** is a portable cybersecurity and RF research platform designed for authorized security research, CTF environments, electronics experimentation, spectrum analysis, and controlled laboratory testing.

The device combines a Raspberry Pi 5, LimeSDR Mini 2.0, ESP32-S3, CC1101 sub-GHz transceiver, touchscreen interface, and USB-C power management inside a custom enclosure.

The project will also help me develop practical skills in Linux, embedded systems, electronics, RF technology, CAD, 3D printing, mechanical design, and cybersecurity.

All cybersecurity and RF experimentation will be performed only on systems, devices, networks, and frequencies where I have authorization to experiment.

---

## Why I Need a 3D Printer

A **3D printer is one of the key manufacturing tools for this project**.

The electronic modules have different dimensions and mounting arrangements, so I need a custom enclosure rather than a standard off-the-shelf case.

The 3D printer will allow me to manufacture:

* Main chassis frame
* Touchscreen bezel
* Raspberry Pi support bracket
* ESP32-S3 mounting bracket
* CC1101 mounting bracket
* Antenna mounting bay
* Cable-routing structures
* Protective outer shell

The printer will also allow me to quickly prototype, test, modify, and reprint components as the design develops.

---

## Role of the 3D Printer

The printer will be involved throughout the engineering process.

### Mechanical Prototyping

I can print small prototypes to check:

* Component dimensions
* Mounting-hole locations
* Screen alignment
* Board clearances
* Cable routing
* Connector access

### Custom Enclosure

The final printed enclosure will hold and protect the electronics while keeping the device compact and portable.

### Modular Mounting

Individual brackets will allow components to be removed or replaced without redesigning the entire enclosure.

### Iterative Development

If something does not fit correctly, I can modify the CAD model and produce another prototype.

This makes the printer an important part of the development cycle.

---

## Materials

### PETG

PETG will be considered for structural components such as the chassis and electronics brackets because of its useful durability and ease of printing.

### PLA

PLA may be used for early prototypes, display components, and cosmetic parts where appropriate.

### ABS

ABS may be used for components where greater temperature resistance is useful, provided the printer and printing environment are suitable.

---

## Required Tools

### Manufacturing

* PETG/ABS-capable 3D printer
* Slicer software
* CAD/modeling software

### Electronics

* Fine-tip soldering iron
* Heat-set insert tip
* Precision wire strippers
* Multimeter

### Mechanical Assembly

* M3 hex key set
* Phillips/flat-head screwdriver set

---

## Manufacturing Workflow

```text
CAD Design
    ↓
Prototype Print
    ↓
Dimensional Test
    ↓
Modify Design
    ↓
Final Print
    ↓
Heat-Set Inserts
    ↓
Mechanical Assembly
    ↓
Electronics Installation
    ↓
Testing
```

The mechanical design will be developed alongside the electronics instead of being treated as something completed only at the end.

---

## Development Approach

I will develop the project iteratively:

1. Design
2. Prototype
3. Test
4. Identify problems
5. Modify the design
6. Reprint
7. Assemble
8. Test again
9. Document the results

This approach allows the physical design to evolve together with the electronics and software.

---

## Initial Fabrication Plan

The first fabrication stage will involve creating and testing:

* Main chassis
* Display bezel
* SBC support bracket
* Antenna mounting bay
* RF co-processor mount
* Sub-GHz radio mount
* Outer shell

After printing, the parts will be inspected for dimensional accuracy, warping, layer quality, mounting-hole accuracy, and fit.

M3 heat-set inserts will then be installed where required.

---

## Responsible Use

Although the project is named **Universal Hacking Tool**, its purpose is legitimate cybersecurity education and authorized research.

The platform will be used for:

* Personal cybersecurity labs
* Capture-the-Flag competitions
* Electronics experimentation
* RF education
* Spectrum analysis
* Embedded-system research
* Testing devices and systems that I own or have explicit permission to test

I will not use the project to gain unauthorized access to computers, networks, accounts, communications, or other people's devices.

---

## Current Status

**Phase:** Planning and design

**Progress:** Initial project architecture and manufacturing plan completed.

**Next step:** Finalize the enclosure/CAD design and begin prototyping the 3D-printed components.
