## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name: YUVAN SHANKAR RAM K R  |  | **Reg. No.: 26017383  |  |
|---|---|---|---|
| **Date: 17-11-2026  | | **Batch / Section: BE-CSE  | |

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

<img width="1280" height="563" alt="KVL" src="https://github.com/user-attachments/assets/24398d69-f1cb-4088-b739-c89683a5b401" />


**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="1280" height="691" alt="KCL" src="https://github.com/user-attachments/assets/80523dac-d9a1-4fd3-aa38-b0210e029812" />


**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

<img width="1510" height="837" alt="KVL proties" src="https://github.com/user-attachments/assets/57554720-fd8d-4243-9856-e91c552cd96c" />


**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="1235" height="710" alt="KCL proties" src="https://github.com/user-attachments/assets/a8fea4c1-a132-4559-b417-029cef150420" />


**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

<img width="1280" height="575" alt="KVL table" src="https://github.com/user-attachments/assets/08708a11-83a8-44ce-83cb-fda1b723c07a" />


### B. KCL – Current measurements

<img width="1280" height="613" alt="KCL table" src="https://github.com/user-attachments/assets/f0632b6e-4fd3-4795-a4f9-89486f9c342c" />


## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.


<img width="956" height="1280" alt="KVL calculation" src="https://github.com/user-attachments/assets/a2663aed-050e-4576-bd07-a5e5aba708b7" />


**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.


<img width="1402" height="1122" alt="KCL calculation1" src="https://github.com/user-attachments/assets/d90bc4a0-4c35-4c1d-a7a8-8a1beec5b52a" />


**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
