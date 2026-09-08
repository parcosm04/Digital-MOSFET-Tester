# 🔌 Digital MOSFET Tester

A simple and practical circuit designed to identify and test N-Channel and P-Channel MOSFETs and observe their switching behavior.

## 📌 Overview

MOSFETs are widely used as electronic switches in applications such as SMPS, motor drivers, battery management systems, DC-DC converters, and embedded systems.

Correctly identifying the MOSFET type and its Gate, Drain, and Source terminals is essential before integrating a device into a circuit.

This project demonstrates MOSFET identification using a simple LED-based testing circuit rather than relying on complex measurement instruments.

## 🎯 Objectives

- Identify N-Channel and P-Channel MOSFETs
- Verify MOSFET switching behavior
- Demonstrate the effect of gate voltage on MOSFET operation
- Reduce incorrect MOSFET connections
- Develop practical understanding of MOSFET operation

## ⚙️ Components Used

| Component | Value / Part |
|---|---|
| Battery | 9V |
| MOSFET | 2N7000 |
| LED 1 | Green LED |
| LED 2 | Red LED |
| R1 | 220Ω |
| R2 | 1kΩ |
| R3 | 10kΩ |
| S1 | Slide Switch |
| S2 | Push Button |

## 🔌 Circuit Diagram and Working

![Digital MOSFET Tester](circuit/digital-mosfet-tester.png)

## 🧠 Working Principle

The tester uses a mode-selection switch to select the intended MOSFET test mode. The MOSFET under test is inserted into the test socket with the correct Gate, Drain, and Source orientation. When the test button is pressed, a gate voltage is applied and the LEDs provide a visual indication of the resulting switching behavior.

The infographic included in this repository summarizes the circuit, components, working sequence, LED indications, and key learnings.

## 📊 Test Indications

- **N-Channel mode:** Green LED indicates an N-Channel MOSFET detected; red LED indicates a wrong device or connection.
- **P-Channel mode:** Red LED indicates a P-Channel MOSFET detected; green LED indicates a wrong device or connection.
- **Without pressing the test button:** both LEDs may indicate a shorted or faulty device.

## 💡 Key Learnings

- MOSFET switching behavior and gate control
- N-Channel vs P-Channel MOSFET operation
- Identifying Gate, Drain and Source terminals
- Practical circuit debugging and component testing
- Connecting semiconductor devices correctly before use

## 🚀 Future Improvements

- Support for a wider range of MOSFETs
- Automatic MOSFET type detection
- Digital display for test results
- MOSFET threshold / electrical parameter measurement
- Microcontroller-based testing
- Dedicated PCB implementation

## 👨‍💻 Contributors

**Pankaj Pandit** — Electronics & Telecommunication Engineering  
**Harshwardhan Chitte** — Project collaborator

This project was developed collaboratively for practical learning and demonstration of MOSFET operation.

## 📜 License

This project is intended for educational purposes.
