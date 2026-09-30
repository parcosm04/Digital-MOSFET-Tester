<div align="center">

# 🔌 Digital MOSFET Tester

### A Compact Hardware Tool for MOSFET Identification & Switching Tests

**N-Channel · P-Channel · Gate Control · Switching Behaviour**

<br>

<a href="https://github.com/parcosm04/Digital-MOSFET-Tester">
<img src="https://img.shields.io/badge/GITHUB-111827?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<img src="https://img.shields.io/badge/HARDWARE-FFB000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MOSFET-7C3AED?style=for-the-badge"/>
<img src="https://img.shields.io/badge/ELECTRONICS-00E5FF?style=for-the-badge"/>

</div>

---

## ⚡ Project Overview

The **Digital MOSFET Tester** is a compact hardware circuit designed to test and identify **N-Channel and P-Channel MOSFETs** while demonstrating their switching behaviour.

Instead of relying on laboratory instruments, the tester uses **gate control and LED-based visual indications** to determine the response of the device under test.

The project focuses on understanding the practical behaviour of MOSFETs as **voltage-controlled electronic switches**.

---

## 🧠 What It Tests

<div align="center">

| Test | Purpose |
|:---|:---|
| 🔀 **MOSFET Type** | N-Channel / P-Channel identification |
| ⚡ **Gate Control** | Applies the required gate condition |
| 💡 **Switching** | Observes ON/OFF behaviour |
| 🔴🟢 **LED Indication** | Provides visual test feedback |
| 🔌 **Pin Orientation** | Helps verify correct G-D-S connection |

</div>

---

## ⚙️ Working Principle

The MOSFET under test is inserted into the tester with its **Gate, Drain and Source** terminals correctly oriented.

A mode-selection switch determines the intended test configuration.

When the test button is pressed:

```text
        MODE SELECT
             │
             ▼
      ┌─────────────┐
      │ MOSFET DUT  │
      │  G  D  S    │
      └──────┬──────┘
             │
       Gate Control
             │
             ▼
       Switching State
             │
             ▼
        LED Indication
````

The LEDs provide a simple visual indication of the resulting switching behaviour.

---

## 🔬 Test Logic

### N-Channel Mode

```text
Correct N-MOSFET
      ↓
Gate condition applied
      ↓
MOSFET switches
      ↓
🟢 Green LED
```

A red indication can represent an incorrect device or connection.

### P-Channel Mode

```text
Correct P-MOSFET
      ↓
Gate condition applied
      ↓
MOSFET switches
      ↓
🔴 Red LED
```

A green indication can represent an incorrect device or connection.

The LED behaviour therefore provides a quick hardware-level indication without requiring a dedicated measurement instrument.

---

## 🧩 Hardware

<div align="center">

| Component  | Specification |
| :--------- | :-----------: |
| 🔋 Battery |      `9V`     |
| 🔌 MOSFET  |    `2N7000`   |
| 🟢 LED 1   |     Green     |
| 🔴 LED 2   |      Red      |
| R1         |     `220Ω`    |
| R2         |     `1kΩ`     |
| R3         |     `10kΩ`    |
| S1         |  Slide Switch |
| S2         |  Push Button  |

</div>

---

## 🔌 Circuit Concept

The circuit combines:

```text
        9V SUPPLY
            │
            ▼
     ┌──────────────┐
     │ MODE SELECT  │
     └──────┬───────┘
            │
            ▼
     ┌──────────────┐
     │ MOSFET DUT   │
     └──────┬───────┘
            │
       GATE CONTROL
            │
            ▼
     ┌──────────────┐
     │ LED OUTPUT   │
     └──────────────┘
```

The design demonstrates how **gate voltage controls MOSFET conduction**, translating the electrical behaviour into an easily observable visual output.

---

## 🛠️ Engineering Concepts

<div align="center">

`MOSFET Switching` · `Gate Control` · `N-Channel` · `P-Channel`

`Voltage-Controlled Devices` · `Pull-Up / Pull-Down` · `Current Limiting`

`Hardware Testing` · `Circuit Debugging` · `Component Identification`

</div>

---

## 💡 Key Learning

This project provided practical understanding of:

* MOSFET as a switching device
* Difference between N-Channel and P-Channel operation
* Gate, Drain and Source identification
* Gate-voltage-dependent switching
* LED-based hardware indication
* Resistor selection for current limiting and gate biasing
* Practical component testing and circuit debugging

---

## 🚀 Future Development

The current design can be extended into a more advanced semiconductor testing platform.

```text
Current Tester
      │
      ├── Automatic MOSFET Detection
      ├── Wider MOSFET Compatibility
      ├── Digital Result Display
      ├── Threshold Voltage Measurement
      ├── Electrical Parameter Testing
      ├── Microcontroller Integration
      └── Dedicated PCB
```

Potential future measurements include:

`VGS(th)` · `RDS(on)` · `Gate Response` · `Switching Behaviour`

---

## 👥 Contributors

**Pankaj Pandit**
Electronics & Telecommunication Engineering

**Harshwardhan Chitte**
Project Collaborator

Developed as a practical electronics project to explore **MOSFET operation, switching circuits, and hardware testing**.

---

<div align="center">

### ⚡ TEST. SWITCH. UNDERSTAND.

`Hardware` · `MOSFETs` · `Digital Electronics` · `Circuit Testing`

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00E5FF,50:7C3AED,100:FFB000&height=100&section=footer"/>

</div>
