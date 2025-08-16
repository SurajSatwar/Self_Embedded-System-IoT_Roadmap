# A1 – Basic Electronics

##  Notes

### Ohm’s Law
- Formula: V = I × R
- Voltage (V): Push of electricity
- Current (I): Flow of electrons
- Resistance (R): Opposition to flow
- Why: Helps size resistors (e.g., for LEDs)

**Example:**  
Supply = 5V, LED drop = 2V, Current = 10mA  
R = (5 – 2) / 0.01 = 300Ω → Use 330Ω



### Pull-up / Pull-down Resistors
- Keep input pins at a known level when switch open.
- Pull-up → tied to Vcc → default HIGH
- Pull-down → tied to GND → default LOW
- Typical values: 4.7kΩ – 10kΩ



### Decoupling Capacitors
- Small caps (0.1µF): Remove high-frequency noise.
- Larger caps (10µF+): Smooth sudden dips.
- Always place near MCU power pins.



### LDO vs Switching Regulators
- **LDO:** Simple, low noise, less efficient.
- **Switching Regulator:** High efficiency, adds ripple, more complex.



##  Practical
- Build LED + resistor circuit.
- Add button with pull-up.
- Measure voltage/current using multimeter.
- Add debounce in code.



##  Summary
- Use Ohm’s Law for resistor sizing.
- Pull-ups/pull-downs stabilize inputs.
- Decoupling caps improve power.
- Choose regulator depending on noise vs efficiency.



##  References
- [SparkFun Electronics Basics](https://learn.sparkfun.com/tutorials)  
- [All About Circuits – Basic Concepts](https://www.allaboutcircuits.com/textbook/)  
- [GreatScott! Electronics Basics (YouTube)](https://www.youtube.com/watch?v=J4oO7PT_nzQ)  
- [Pull-up & Pull-down Explained (YouTube)](https://www.youtube.com/watch?v=9u0A9z9V0GU)
