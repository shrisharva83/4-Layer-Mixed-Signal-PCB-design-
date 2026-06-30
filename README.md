# Mixed-Signal PCB Design

This project is a 4-layer mixed-signal printed circuit board (PCB) engineered for low-frequency signal analysis and arbitrary signal generation. Designed around the STM32 microcontroller, it serves as a single-channel tool optimized specifically for the audio frequency band (20Hz – 20kHz).

To achieve low-noise performance without relying on bulky external power supplies, the board operates entirely via USB Type-C bus power (consuming under 500mA). It strictly separates its digital and analog domains through careful power supply routing and utilizes dedicated, high-resolution external converters to ensure clean data sampling at the Nyquist limit.

---
**License**
This project is licensed under the [MIT License](LICENSE).
