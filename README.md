## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name: AATHISH J |  | **Reg. No.: 26013781 |  |
|---|---|---|---|
| **Date: 17-11-2026 | | **Batch / Section: B.E Cse | |

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

<img width="1599" height="588" alt="KVL" src="https://github.com/user-attachments/assets/bca4bc57-3a13-472c-a2c1-e29a193cb042" />


**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="1600" height="900" alt="KCL" src="https://github.com/user-attachments/assets/675327fe-4887-4d4a-ba05-34115d49674c" />

**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

<img width="1312" height="710" alt="kvl proteus1" src="https://github.com/user-attachments/assets/9c6cb9ad-02ac-4f84-8418-57549cdae48b" />


**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="1269" height="677" alt="kcl proteus" src="https://github.com/user-attachments/assets/78a55267-ce68-412e-9edb-ad28a328e710" />


**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

<img width="1600" height="545" alt="WhatsApp Image 2026-11-17 at 8 16 14 PM (1)" src="https://github.com/user-attachments/assets/36bc0e99-6b8c-4306-814e-174eff596f1e" />


### B. KCL – Current measurements

<img width="1600" height="442" alt="WhatsApp Image 2026-11-17 at 8 16 14 PM" src="https://github.com/user-attachments/assets/a418f41a-c792-423e-adaf-c85556929732" />


## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

<img width="900" height="500" alt="WhatsApp Image 2026-11-17 at 8 16 16 PM" src="https://github.com/user-attachments/assets/c258a5ed-b5c5-4b04-b243-6ed330443282" />


**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="1200" height="1600" alt="result" src="https://github.com/user-attachments/assets/dcf865a5-005b-4b1e-90bc-001f8a12b4f9" />


**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
