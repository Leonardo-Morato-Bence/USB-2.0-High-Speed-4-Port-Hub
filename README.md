# USB-2.0-High-Speed-4-Port-Hub
High-Efficiency Li-Ion Charger with Integrated Power Path Management and Protection

## Overview

This project implements a USB 2.0 High-Speed hub capable of expanding a single upstream USB connection into four downstream ports while maintaining full USB 2.0 High-Speed (480 Mbps) operation.

The design focuses on:

High-speed signal integrity
Controlled impedance routing
Differential pair matching
Power distribution optimization
EMC-oriented PCB layout techniques

## Features

USB 2.0 High-Speed (480 Mbps)
4 downstream USB ports
Self-powered operation
4-layer PCB
90 Ω differential impedance routing
Ground plane reference
Ferrite bead power filtering
Local decoupling network

##Technical Specifications

Parameter	Value
USB Standard	| USB 2.0 High-Speed
Data Rate	480 Mbps
Ports	4
Power Mode	Self-Powered
PCB Layers	4
Dimensions	75 mm × 50 mm
Main Components
Component	Function
GL850G	USB Hub Controller
USB6B1RL	ESD Protection
12 MHz Crystal	Hub Clock Source
Ferrite Beads	Power Filtering
PCB Design Highlights
Controlled Impedance

USB differential pairs were routed with a target impedance of:

90 Ω differential
Continuous ground reference plane
Length matching within 0.5 mm
Stackup
L1: High-speed signals
L2: Ground plane
L3: Power plane
L4: Control and low-speed signals
Validation

The hub was tested using USB flash drive file transfers.

Measured transfer rate:

Approximately 23 MB/s

This result is consistent with expected USB 2.0 High-Speed storage performance.

Documentation

Full datasheet available in:

Datasheet/USB_2.0_High-Speed_4-Port_Hub_v1.0.pdf

Future Improvements
Per-port current limiting
USB-C upstream interface
Power monitoring
Status LEDs per port
