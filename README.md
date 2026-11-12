## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:** |THESHWIN P S| **Reg. No.:** |26005632 |
|---|---|---|---|
| **Date:** |12-11-2026 | **Batch / Section:** |26ODJ084 |

---

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Component | Range / Rating | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Resistor | 1 kΩ | 3 |
| 2 | DC Voltmeter | 0–30 V | 3 |
| 3 | DC Ammeter | 0–0.2 A | 3 |
| 4 | Breadboard | — | 1 |
| 5 | Regulated Power Supply (RPS) | 0–30 V | 1 |
| 6 | Connecting wires | As required | As required |
| 7 | Simulation software | Proteus Design Suite | 1 |

## THEORY

**Kirchhoff's Voltage Law (KVL):** The algebraic sum of all voltage rises and voltage drops around any closed loop in an electrical circuit is zero.

**Kirchhoff's Current Law (KCL):** The algebraic sum of currents at any node is zero. In other words, the total current entering a node is equal to the total current leaving the node.

## PROCEDURE

### A. Verification of KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Ensure that the RPS output is set to zero volts before switching it on.
3. Check that all meters are correctly connected and set to their zero positions.
4. Switch on the RPS and gradually set the required input voltage within the specified range.
5. Measure and record the voltage across each resistor using the voltmeters.
6. Repeat the measurements for different input-voltage values and tabulate the readings.

### B. Verification of KCL

7. Connect the circuit as shown in the KCL circuit diagram.
8. Ensure that the RPS output is set to zero volts before switching it on.
9. Check that all meters are correctly connected and set to their zero positions.
10. Switch on the RPS and gradually set the required input voltage within the specified range.
11. Measure and record the current in each branch using the ammeters.
12. Repeat the measurements for different input-voltage values and tabulate the readings.

## CIRCUIT DIAGRAMS

### A. KVL circuit diagram

<img width="415" height="408" alt="Screenshot 2026-11-12 185437" src="https://github.com/user-attachments/assets/c968ac78-9f49-4217-b3ba-347ab8927a4e" />



**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="402" height="515" alt="image" src="https://github.com/user-attachments/assets/23ff4eab-4511-4fbd-8c2a-aeb0ffdaedcc" />

**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

<img width="1202" height="858" alt="Screenshot 2026-11-12 184333" src="https://github.com/user-attachments/assets/bb627bd1-1c36-4c67-bfae-e7936490f284" />


**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="1438" height="772" alt="Screenshot 2026-11-12 184409" src="https://github.com/user-attachments/assets/7fc2085e-5278-4468-8a17-4545e8a1b2ff" />


**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

| S. No. | Supply voltage Vs (V) | VR1 (V) | VR2 (V) | VR3 (V) | VR1 + VR2 + VR3 (V) |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

### B. KCL – Current measurements

| S. No. | Supply voltage Vs (V) | Total current It (A) | Branch current I1 (A) | Branch current I2 (A) | Branch current I3 (A) | I1 + I2 + I3 (A) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | | | | | | |
| 2 | | | | | | |
| 3 | | | | | | |
| 4 | | | | | | |
| 5 | | | | | | |

## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

<img width="372" height="257" alt="Screenshot 2026-11-12 185353" src="https://github.com/user-attachments/assets/fff38645-7771-4f88-83c3-a2223f4ab9dc" />
<img width="387" height="121" alt="Screenshot 2026-11-12 185425" src="https://github.com/user-attachments/assets/e3824f94-abe4-4009-9492-300cce4eda9a" />


**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="381" height="375" alt="Screenshot 2026-11-12 185803" src="https://github.com/user-attachments/assets/f17b71bd-79c0-4e65-b9c6-e1182a5f5005" />
<img width="330" height="292" alt="Screenshot 2026-11-12 185815" src="https://github.com/user-attachments/assets/43c28985-7bb5-4166-88e8-200649802c36" />


**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
