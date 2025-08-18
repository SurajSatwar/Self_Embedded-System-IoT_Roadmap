# A4 – Embedded C Advanced

##  What to Study
- `volatile`, `const`, `static`, linkage
- Bitwise operations, masks, shifts, endianness
- Structs, unions, bitfields, function pointers
- Stack vs heap, memory layout (text, data, bss)



##  Practical Labs
1. **Register-Mapped GPIO Driver**  
   - Use STM32 or PIC18 with `volatile` pointers  
   - Example: `#define GPIOA_ODR (*(volatile uint32_t*)0x48000014)`

2. **Toolchain Exploration**  
   - Compile using `arm-none-eabi-gcc`  
   - Inspect `.map` file for RAM/Flash usage  
   - Use Makefile or CMake to automate



##  Completed External Course
I completed the **“Basics of Embedded C Programming”** course from **MindLuster** ✅  
- Topics covered (from course lessons):  
  - Difference between C & Embedded C  
  - Bitwise operators, masking, extracting, monitoring  
  - 8051 architecture basics  
  - KEIL IDE, coding & burning process  
- Certificate earned (see repo `/certificates/` folder)




##  References
- [MindLuster – Basics of Embedded C Programming](https://www.mindluster.com/lesson/23445-video)
- [ARM GCC Toolchain Docs](https://developer.arm.com/downloads/-/arm-gnu-toolchain-downloads)
- [STM32 Programming Guide (ST)](https://www.st.com/en/development-tools/stm32cubeide.html)
