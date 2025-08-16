# A2 – Digital Logic & Signal Basics

##  Notes

### Logic Levels
- TTL (5V): HIGH ≥ 2.0V, LOW ≤ 0.8V
- CMOS (3.3V): HIGH ~0.7 × Vcc, LOW ~0.3 × Vcc
- Always check VIH/VIL in datasheet.



### Analog vs Digital
- Analog: Continuous range (sensor voltages).
- Digital: Only 0 or 1.



### Schmitt Trigger
- Adds hysteresis (two thresholds).
- Cleans noisy, slow edges.
- Prevents false triggers.



### Level Shifting
- Required when devices use different voltages.
- Options:
  - Voltage divider
  - MOSFET-based shifter (I²C/SPI)
  - Dedicated ICs



## 🔧 Practical
- Make truth tables (AND, OR, NOT, NAND, XOR).
- Build MOSFET-based I²C level shifter.
- Simulate noisy signal with Schmitt trigger.



##  Summary
- Logic thresholds vary by family.
- Schmitt triggers stabilize signals.
- Level shifting protects devices.



##  References
- [Logic Gate Basics](https://www.electronics-tutorials.ws/logic/logic_1.html)  
- [Level Shifting Guide (SparkFun)](https://www.sparkfun.com/tutorials/65)  
- [Logic Gates Explained (YouTube)](https://www.youtube.com/watch?v=CI2Xk7fLQpM)  
- [Level Shifting for MCUs (YouTube)](https://www.youtube.com/watch?v=n9cfTnvCy-8)
