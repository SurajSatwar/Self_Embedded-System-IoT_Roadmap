#  LEVEL C — PERIPHERALS & REGISTERS

This level focuses on **mastering microcontroller peripherals** (GPIO, Timers, UART, ADC, I²C, SPI, LCD, RTC) at **register level**.  
These are the building blocks for any embedded firmware engineer.  



##  Topics Covered

### C.1 GPIO (General Purpose I/O)
- Modes: input, output, open-drain, pull-up/pull-down.
- Debouncing (hardware & software).
- Alternate functions for communication peripherals.
- **Practical**: LED blink, button input, LED toggle on button press.

### C.2 Timers & PWM
- Timer basics: prescaler, auto-reload, counter.
- PWM generation.
- Input capture for measuring signal frequency.
- **Practical**: LED fading with PWM, timer-based square wave.

### C.3 UART (Serial Communication)
- Baud rate, parity, start/stop bits.
- Polling vs interrupt-driven UART.
- **Practical**: Send "Hello" to PC, echo received characters.

### C.4 ADC (Analog-to-Digital Converter)
- Resolution, reference voltage, sampling time.
- **Practical**: Read potentiometer → control LED brightness; print values via UART.

### C.5 SPI (Serial Peripheral Interface)
- Master/slave, MOSI/MISO/SCK/CS.
- **Practical**: Write/read to an EEPROM or sensor (like a temperature sensor).

### C.6 I²C (Inter-Integrated Circuit)
- Master/slave, addressing, SDA/SCL.
- **Practical**: Communicate with RTC (DS1307) or sensor (MPU6050).

### C.7 LCD (16x2 Character Display)
- Command/data instructions.
- Sending strings, cursor positioning.
- **Practical**: Display "Hello World" and sensor values.

### C.8 RTC (Real-Time Clock)
- Using I²C with RTC modules.
- **Practical**: Display time on LCD via RTC (DS1307).



##  Program Structure (Function Prototypes)

Each concept follows this standard flow:

### Example: LCD with I²C + RTC
// Function Prototypes
void delay(int);
void lcd_init(void);
void lcd_cmd(unsigned char);
void lcd_data(unsigned char);
void lcd_string(unsigned char *p);
void rtc_init(void);
void rtc_write(void);
void rtc_time(void);
void start(void);
void stop(void);
void check(void);
void i2c_data(char);
void i2c_read(void);
void display(void);
