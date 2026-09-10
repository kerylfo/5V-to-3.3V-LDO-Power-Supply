# 5V to 3.3V LDO Power Supply Module (LT1117)

A compact, 5V-to-3.3V linear regulator PCB designed in KiCad, validated with LTspice, and optimized for thermal and EMI performance.

![3D PCB Render](docs/board_3d.png)

## Specifications
* **Input Voltage:** 5.0V
* **Output Voltage:** 3.3V DC
* **Regulator:** LT1117-3.3 (SOT-223)
* **Power Trace Width:** 0.2 mm
* **Grounding:** Continuous bottom ground plane (`B.Cu`) with low-impedance via stitching

## Bill of Materials
| Ref | Qty | Part | Footprint |
| :--- | :--- | :--- | :--- |
| U1 | 1 | LT1117-3.3 | SOT-223 |
| C1, C2 | 2 | 10µF Capacitor | 0805 |
| R1 | 1 | 330Ω Resistor | 0805 |
