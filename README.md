# STM32F103C8T6 4-Layer Development Board

A **high-quality, handsolderable 4-layer STM32F103C8T6 development board** designed for prototyping and integration with custom carrier boards.

---

## Key Features

- **Microcontroller:** STM32F103C8T6 (ARM Cortex-M3)  
- **PCB:** 4-layer design for improved signal integrity and grounding  
- **Power:** USB-C input with **separate digital and analog power rails**  
- **User Interface:** 1 user push-button, 1 reset button, and 2 user-configurable LEDs  
- **Connectivity:** Both male and female headers for flexible I/O access  
- **Programming & Debugging:**  
  - Native USB programming (no external programmer required)  
  - Dedicated SWD header for alternative programming or debugging  
- **Boot Options:** BOOT header for selecting boot mode (e.g., built-in bootloader or flash)  
- **Assembly:** Fully handsolderable layout suitable for DIY prototyping  
- **Form Factor:** Compact design for breadboarding or integration into larger systems  

---

## Technical Specifications

| Feature           | Description                        |
|------------------|------------------------------------|
| MCU               | STM32F103C8T6 (Cortex-M3)          |
| Power             | 5 V via USB-C                       |
| Power Rails       | Separate digital and analog rails   |
| User Button       | 1 push-button                       |
| Reset Button      | 1 push-button                       |
| User LEDs         | 2 LEDs, user-configurable           |
| SWD Header        | Yes                                 |
| BOOT Header       | Yes, for boot mode selection        |
| Programming       | Native USB or SWD                   |
| PCB Layers        | 4                                  |
| I/O Access        | Male and female headers             |
| Dimensions        | *Specify dimensions here*           |

---

## Applications

This development board is suitable for:  

- Embedded systems prototyping  
- Educational or laboratory projects  
- Carrier board integration for modular systems  
- Firmware and hardware testing in development environments  

---

## Getting Started

1. Connect the board via USB-C for power and programming.  
2. Flash firmware using either **native USB programming** or via the **SWD header** with STM32CubeProgrammer, OpenOCD, or dfu-util.  
3. Utilize the SWD header for debugging or development tasks.  
4. Use the reset button to restart the MCU and the user button/LEDs for custom interactions.  
5. Configure the BOOT header to select the desired boot mode for the MCU.  
6. Access the headers to connect sensors, displays, or additional peripherals.  

> ⚡ The separate analog and digital power rails reduce noise for sensitive analog applications.

---

## Reference Video

For a comprehensive walkthrough, see the following video: [YouTube – STM32F103C8T6 Dev Board Walkthrough](https://www.youtube.com/watch?v=PMEpQZ90f34&t=9428s)

---

## Repository Contents

- `/hardware` — KiCad design files (schematics + PCB layout)  
- `/firmware` — Example STM32 projects  
- `/docs` — Datasheets, pinouts, and assembly instructions  
- `/images` — Board renders and photographs  

---

## License

- **MIT License**

---

## Author

Designed by [Oliver Studman] – built for robust prototyping and open hardware experimentation.
