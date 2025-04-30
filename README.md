# AC to DC Converter Circuit (5V Output)
![photo7](https://github.com/user-attachments/assets/70441a27-e07a-4aaa-829d-77ac3e148655)

This project demonstrates a simple AC to DC converter circuit using a bridge rectifier and a 7805 voltage regulator. The output is a regulated 5V DC, suitable for powering microcontrollers or other 5V logic circuits.

---

## 🧰 Components Used

| Component | Description             |
|-----------|-------------------------|
| D1, D3, D4, D5 | 1N4007 Diodes (Bridge Rectifier) |
| C1        | Electrolytic Capacitor (for filtering) |
| U1        | 7805 Voltage Regulator (5V output) |
| R1        | Current Limiting Resistor for LED |
| D2        | LED (Power indicator) |
| J1        | 2-pin Connector (AC Input) |
| PWR_FLAG  | Power flag (used in PCB design software) |

---

## ⚙️ Working Principle

1. **AC Input**: The AC voltage is applied at the connector `J1` (Input1 and Input2).
2. **Bridge Rectifier**: Diodes D1, D3, D4, and D5 form a bridge rectifier to convert the AC voltage to pulsating DC.
3. **Smoothing**: Capacitor C1 filters the pulsating DC and provides a smoother DC output.
4. **Voltage Regulation**: The 7805 IC (U1) regulates the voltage to a constant 5V DC.
5. **Power Indication**: LED D2 lights up when the 5V output is active. R1 limits the current to the LED.

---

## 🔌 Output

- **DC Output Voltage**: 5V (regulated)
- **Usable For**: Powering 5V devices like Arduino, sensors, or microcontrollers.

---
![photo5](https://github.com/user-attachments/assets/8ad9a782-dbfa-457c-8808-a914854afa94)
![photo6](https://github.com/user-attachments/assets/55294e58-2dc2-4741-aa22-48b87a99e8d3)

