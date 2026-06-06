# USB 2.0 High-Speed 4-Port Hub

Self-powered 4-port USB 2.0 High-Speed hub with controlled impedance PCB
design

---

## Overview

The USB 2.0 High-Speed 4-Port Hub is designed to expand a single USB connection into four downstream ports while maintaining full USB 2.0 High-Speed operation (480 Mbps).

This project focuses on practical high-speed PCB design techniques, including controlled impedance routing, differential pair matching, power integrity optimization, and EMC-oriented layout practices.

The design serves both as a functional USB expansion module and as a reference implementation for USB 2.0 High-Speed hardware design.

---

## Features

- USB 2.0 High-Speed (480 Mbps)
- 4 downstream USB ports
- Self-powered architecture
- 4-layer PCB design
- Controlled differential impedance routing
- Continuous ground reference plane
- Differential pair length matching
- Local decoupling network
- Ferrite bead power filtering
- Signal integrity optimized layout

---

## Technical Specifications

| Parameter | Value |
|-----------|--------|
| USB Standard | USB 2.0 High-Speed |
| Data Rate | 480 Mbps |
| Downstream Ports | 4 |
| Power Mode | Self-Powered |
| Input Voltage | 5 V |
| Maximum Total Output Current | 2 A |
| PCB Layers | 4 |
| Dimensions | 75 mm × 50 mm |

---

## PCB Stackup

| Layer | Function |
|---------|---------|
| L1 | High-speed signals |
| L2 | Ground plane |
| L3 | Power plane |
| L4 | Control and low-speed signals |

---

## Design Highlights

### Controlled Impedance Routing

All USB differential pairs were routed with:

- 90 Ω differential impedance target
- Continuous ground reference plane
- Minimized discontinuities
- Length matching within 0.5 mm

### Signal Integrity

Special attention was given to:

- Differential pair matching
- Return current paths
- Via placement
- Ground stitching
- Noise reduction

### Power Integrity

The power distribution network includes:

- Dedicated power plane
- Local decoupling capacitors
- Ferrite bead filtering
- Bulk capacitance

---

## Main Components

| Component | Function |
|-----------|----------|
| GL850G | USB Hub Controller |
| USB6B1RL | USB ESD Protection |
| 12 MHz Crystal | Hub Clock Source |
| Ferrite Beads | Power Filtering |

---

## Hardware Images

### PCB Assembly

<img width="788" height="537" alt="image" src="https://github.com/user-attachments/assets/782bfe36-75a0-475f-a3d1-4af0f7556023" />

### 3D PCB View

<img width="1072" height="669" alt="image" src="https://github.com/user-attachments/assets/f136346c-2be3-49c6-8d1e-39c3157fb94a" />

### Top Layer

<img width="901" height="563" alt="image" src="https://github.com/user-attachments/assets/428aabdb-f914-414e-9f45-a8f8822520db" />

---

## Validation

The hub was validated through practical USB storage testing.

### USB Flash Drive Transfer Test

- Test device: USB Flash Drive
- Interface: USB 2.0 High-Speed
- Measured transfer rate: ~23 MB/s

The measured performance is consistent with typical USB 2.0 High-Speed storage devices.
