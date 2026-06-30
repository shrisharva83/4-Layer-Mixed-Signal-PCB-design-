# Mixed-Signal PCB Design

This project is a 4-layer mixed-signal printed circuit board (PCB) engineered for low-frequency signal analysis and arbitrary signal generation. Designed around the STM32 microcontroller, it serves as a single-channel tool optimized specifically for the audio frequency band (20Hz – 20kHz).

To achieve low-noise performance without relying on bulky external power supplies, the board operates entirely via USB Type-C bus power (consuming under 500mA). It strictly separates its digital and analog domains through careful power supply routing and utilizes external converters to ensure clean data sampling at the Nyquist limit.

<p align="center">
  <img src="https://github.com/user-attachments/assets/a0b5da0d-c885-49bf-aa40-a8a1a1ee974d" alt="MSDPCBFront" width="49%" />
  <img src="https://github.com/user-attachments/assets/00c378f2-7ef7-4df6-bcc0-2fa7a0768b69" alt="MSDPCBBack" width="49%" />
</p>

---
**License**
This project is licensed under the [MIT License](LICENSE).
