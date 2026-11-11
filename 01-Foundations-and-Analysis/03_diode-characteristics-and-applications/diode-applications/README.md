# Diode Applications

This directory contains LTspice simulations demonstrating practical applications of semiconductor diodes in electronic circuits. The experiments explore how diodes can be used to convert AC signals, shape waveforms, and regulate DC voltage.

## Applications Covered

### 1. Rectifier Circuits
Demonstrates the conversion of AC voltage into pulsating DC voltage.

- **Half-Wave Rectifier:** Uses a single diode to allow current flow during one half-cycle of the input signal.
- **Full-Wave Bridge Rectifier:** Uses four diodes arranged in a bridge configuration to utilize both half-cycles of the AC input.

### 2. Clipper Circuits
Demonstrates how diode circuits limit or remove portions of an input waveform without significantly affecting the remaining waveform.

The simulations cover:
- Positive and negative series clippers.
- Positive and negative parallel clippers.
- Positive and negative biased parallel clippers.
- Two-sided biased clipper.

### 3. Clamper Circuits
Demonstrates how diode-capacitor-resistor networks shift an AC waveform to a different DC reference level while approximately preserving its peak-to-peak amplitude.

- **Positive Clamper:** Shifts the waveform upward.
- **Negative Clamper:** Shifts the waveform downward.

### 4. Zener Voltage Regulator
Demonstrates the use of a reverse-biased Zener diode to maintain an approximately constant output voltage despite variations in input voltage or load conditions.

## Learning Objectives

Through these simulations, the experiments aim to develop an understanding of:

- AC-to-DC conversion using half-wave and full-wave rectification.
- Output voltage behavior and ripple in rectifier circuits.
- Waveform limiting using series, parallel, and biased clippers.
- DC level shifting using positive and negative clampers.
- Voltage regulation using Zener diodes.
- The effects of diode forward voltage, bias voltage, resistance, and capacitance on circuit behavior.

## Directory Structure

```text
diode-applications/
│
├── README.md
│
├── rectifier-circuits/
│   ├── README.md
│   ├── half-wave-rectifier.asc
│   └── full-wave-rectifier.asc
│
├── clipper-circuits/
│   ├── README.md
│   └── [Clipper simulation files]
│
├── clamper-circuits/
│   ├── README.md
│   ├── negative_clamper.asc
│   └── positive_clamper.asc
│
└── zener-voltage-regulator/
    ├── README.md
    └── zener_voltage_regulator.asc
```

## Simulation Environment

All circuits are designed and simulated using **LTspice**. Each subdirectory contains its corresponding circuit schematics and a README describing the circuit configurations and expected behavior.

The simulations provide a practical way to connect diode theory with circuit-level applications and waveform analysis.