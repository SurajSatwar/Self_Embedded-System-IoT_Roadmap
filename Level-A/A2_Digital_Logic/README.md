Digital Logic raedme file
# Level A.2 — Digital Logic & Signals

## Goals
- Read VIH/VIL for TTL vs CMOS and avoid level mistakes
- Use Schmitt triggers when edges are slow/noisy
- Do safe level shifting (5 V ↔ 3.3 V)

## Mini-Labs
1) Truth tables in Falstad: NAND/XOR, screenshots in `/images/`.  
2) Thresholds: save a table of VIH/VIL for TTL, 5V CMOS, 3.3V LVTTL.  
3) Level shifter: BSS138 bidirectional (I²C-style). Note speed limits.  
4) Schmitt demo: RC ramp vs Schmitt input; compare chatter vs clean edge.

## Notes (fill in)
- TTL VIH/VIL: __________
- CMOS VIH/VIL: __________
- When to use translator ICs: __________

## Lessons Learned
- “5 V logic” is not one thing—check thresholds
- Hysteresis prevents multiple triggers on noisy edges
- MOSFET level shifters are for open-drain, low-speed buses

## References
- TI Logic Guide, Schmitt trigger intro (TI), SparkFun level shifting, Falstad links (see A2 notes).
