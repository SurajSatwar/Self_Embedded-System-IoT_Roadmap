# A3 – C Language Basics for Embedded

## 📚 Notes

### Data Types
- Use fixed-width from `<stdint.h>`:
  - `uint8_t` → 0–255
  - `uint16_t` → 0–65535
  - `int32_t` → signed large numbers
- Why: Predictable memory use.

---

### Control Flow
- `if-else`: decisions
- `for`, `while`: loops
- `switch-case`: multiple conditions

---

### Functions & Headers
- `.h` → declarations, macros
- `.c` → implementation
- Modular code structure = easier debugging.

---

### Arrays & Pointers
- Array = collection of values.
- Pointer = stores memory address.
- In embedded: often point to registers or buffers.

---

## 🔧 Practical
- Bare-metal Blink LED + Button counter.
- Increment counter when button pressed.
- Print counter over UART.

---

## 📌 Summary
- Fixed-width types avoid confusion.
- `.h` + `.c` organization is essential.
- Arrays + pointers = hardware access.

---

## 📎 References
- [Embedded C Programming Basics](https://www.geeksforgeeks.org/embedded-c-programming-introduction/)  
- [Pointers in C (Learn-C.org)](https://www.learn-c.org/en/Pointers)  
- [C for Embedded – FastBit Embedded (YouTube)](https://www.youtube.com/watch?v=eJ5jH2QoJ4I)  
- [Pointers Made Easy (YouTube)](https://www.youtube.com/watch?v=2ybLD6_2gKM)
