Basic Electronics Readme file
# Level A.1 — Basic Electronics

## Goals
- Size resistors using Ohm’s law (V = I·R)
- Place local (0.1 µF) + bulk (4.7–47 µF) decoupling capacitors correctly
- Use pull-up / pull-down resistors to avoid floating inputs
- Know when to pick LDO vs switching regulators

## Schematic & BOM
- LED on D6 via 330 Ω to GND
- Pushbutton on D2 to GND; INPUT_PULLUP enabled
- 0.1 µF decoupling near MCU VCC; 10 µF bulk near supply
- Tools: Arduino Uno or STM32 Nucleo, multimeter

## Steps
1) Wire LED + resistor and button (INPUT_PULLUP).  
2) Upload debounce sketch (no `delay()`); verify single toggles.  
3) Measure:
   - V across resistor (expected ~3 V on 5 V system with red LED)
   - LED current (expected ~8–12 mA)
   - Try debounce times (10–50 ms) and record what works best.
4) Optional: add RC + Schmitt trigger for hardware help.

## Results
- V_R = ____
- I_LED = ____ mA
- Debounce window = ____ ms
- Notes & gotchas: ______

## Lessons Learned
- Clean power + clean inputs = stable firmware
- Short traces beat large decoupling values for high-frequency noise
- External pull-ups give predictable behavior vs weak internal pulls

## References
- Khan Academy – Ohm’s law: https://www.khanacademy.org/
- TI – Decoupling capacitors (video): https://www.ti.com/
- SparkFun – Pull-up resistors: https://learn.sparkfun.com/
- Analog Devices – LDO vs SMPS: https://www.analog.com/
- Arduino – Debounce example: https://www.arduino.cc/
