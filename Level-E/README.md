# Level E — RTOS & Multitasking

##  Overview
This level introduces **Real-Time Operating Systems (RTOS)**, focusing on **FreeRTOS**.  
We build multitasking firmware with tasks, semaphores, queues, and RTOS timing features.

---

##  Topics Covered
- RTOS basics: tasks, scheduler, priorities
- Task states & context switching
- Task timing: vTaskDelay, vTaskDelayUntil
- Memory management: Task stacks, heap
- Combining Peripherals + RTOS (ISR → Task, DMA → Task)



##  Practical Exercises
1. LED blink + UART print in separate tasks  
2. Button ISR gives semaphore → toggles LED  
3. Queue between tasks (Producer → Consumer)  
4. Periodic sensor read using `vTaskDelayUntil()`  
5. DMA ISR signals task via semaphore  



##  Hardware / MCU
- STM32 (Nucleo, Blue Pill)  
- ESP32 (FreeRTOS built-in)  



##  Deliverables
- Notes explaining RTOS concepts  
- **Certificate:** [FreeRTOS Simplified: A Beginner's Guide to Develop and Debug FreeRTOS Applications](https://verify.skilljar.com/c/gxixorrc9vc2)  



##  Purpose
- Understand multitasking in embedded systems  
- Build modular, efficient FreeRTOS-based applications  
- Strengthen IoT and real-time embedded system skills  



##  References
- [FreeRTOS Official Docs](https://freertos.org/)  
- [Microchip Developer Help – Harmony 3](https://microchipdeveloper.com/harmony3:redirect)  
- [Microchip MPLAB X IDE Intro](https://microchipdeveloper.com/mplabx:start)  
- [FreeRTOS + STM32 Tutorial](https://deepbluembedded.com/freertos-stm32/)  
