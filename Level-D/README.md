# Level D — Interrupts, DMA & Efficiency

##  Overview
This level focuses on writing **efficient embedded firmware** using interrupts and DMA, instead of polling. It also introduces low-power design for IoT devices.



##  Topics Covered
- **Interrupts**
  - ISR basics
  - NVIC (Nested Vectored Interrupt Controller)
  - External, Timer, UART, ADC interrupts
- **DMA (Direct Memory Access)**
  - Peripheral-to-Memory transfers
  - CPU offloading
  - Example: ADC + DMA, UART + DMA
- **Efficiency & Low Power**
  - Polling vs Interrupt vs DMA
  - Sleep modes, wake-up on interrupt



##  Practical Exercises
1. **Button Interrupt → LED Toggle**  
2. **Timer Interrupt → LED Blink every 1s**  
3. **UART Rx Interrupt → Echo character**  
4. **ADC Interrupt → Read sensor value**  
5. **ADC + DMA → Fill buffer with 100 samples**  
6. **UART + DMA → Send large string without CPU**  
7. **Low Power Mode → Wake MCU on Button Interrupt**



##  Hardware / MCU
- STM32F103 (Blue Pill / Nucleo)
- PIC18F4520
- ESP32 DevKit



##  Deliverables
- `interrupt_button.c`
- `uart_interrupt.c`
- `adc_dma.c`
- Notes with ISR & DMA flow diagrams
- **Templates:** ISR and DMA program structures (see below)

---

##  Program Flow Templates are also mentioned


 Purpose
Write efficient interrupt-driven code.

Master DMA for high-speed, low-power applications.

Prepare for industry-ready IoT systems.

 References
Interrupts in ARM Cortex-M

STM32 External Interrupt Tutorial

DMA Basics
