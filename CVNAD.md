# NGUYEN ANH DUC

**Embedded / IoT Engineer**

📧 [anhducad1111@gmail.com](mailto:anhducad1111@gmail.com)  
📞 0943079599  
🌐 [anhducad1111.github.io](https://anhducad1111.github.io)  
🔗 [GitHub](https://github.com/anhducad1111)  
🔗 [LinkedIn](https://linkedin.com/in/anhducad1111)  
📍 Da Nang, Vietnam  

---

## SUMMARY

Embedded and IoT Engineer with 1.5+ years of hands-on experience in C/C++, ARM Cortex-M platforms (PSoC 6, STM32, ESP32), peripheral & wireless communication (UART up to 1 Mbps, SPI, I²C, BLE GATT, Cellular AT commands), and desktop/mobile HMI tooling (Python PyQt6, C# WPF, Android Kotlin). Focused on hardware-software integration, debugging communication bottlenecks, and building lightweight internal automation tools to eliminate repetitive manual bench testing.

---

## WORK EXPERIENCE

### Junior Firmware Developer (Secondment) | THESIS PTE LTD — Singapore
*Sep 2026 – Present*

- On international secondment via Enable Startup; developed and tested embedded firmware modules and basic control algorithms in C/C++ for ARM Cortex-M targets (PSoC 6, STM32, ESP32) under senior engineer review.
- Verified peripheral interfaces (UART, SPI, I²C, GPIO, ADC) on hardware boards using bench oscilloscope and serial terminal diagnostics.
- Reproduced, debugged, and resolved firmware communication issues and pin-configuration bugs during hardware bench bring-up.
- Built lightweight Python scripts to automate repetitive bench verification steps and log structured test outputs for the engineering team.

---

### Embedded / IoT Engineer | Enable Startup — Da Nang, Vietnam
*Jun 2025 – Present*

- Developed Python (`PyQt6`, `PyQtGraph`) desktop GUIs for 4-channel laser monitoring (60 FPS, 48h continuous test) and 3-axis scanning workflows (500 × 500 grid in < 22 min); resolved chart lag and collaborated on control logic integration.
- Maintained and debugged C# .NET WPF instrumentation & test tools (1 Mbps UART cryogenic monitor, 25-channel 100 Hz binary DAQ, dual-port 921.6k/1M baud PCB tester); fixed UI freezes and COM port disconnects, stabilizing 30 FPS rendering (~140 MB RAM over 48h runs) and < 45s PCB test cycles (vs. 10 min manual).
- Developed the `SensaTuner` Android app (Kotlin, Jetpack Compose) for industrial sensor setup, 60 FPS vibration plots, and BLE GATT OTA updates (MTU 247, `.cyacd`/`.cyacd2` with automatic retry), achieving 100% pass rate across 150+ OTA test cycles.
- Tested and maintained `PSoC 6` firmware + `nRF9160` LTE-M/NB-IoT cellular modem communication over UART AT commands; debugged buffer desync and pin-mapping issues via serial logs and oscilloscope.
- Created lightweight internal automation utilities and Python scripts to streamline repetitive AT-command validation, device flashing, and serial port checks on the test bench.
- Collaborated with hardware engineers and Singapore-based partners across 8+ industrial instrumentation projects on system integration and bench validation.

---

## TECHNICAL SKILLS

- **Embedded & Firmware**: C, C++, ARM Cortex-M, PSoC 6 / 5LP, STM32, ESP32, Bare-metal, Basic RTOS, UART (up to 1 Mbps), SPI, I²C, GPIO, ADC
- **Wireless & Protocols**: BLE GATT (MTU 247, OTA DFU), Cellular IoT (LTE-M / NB-IoT AT Commands), LoRa, MQTT, TCP/IP
- **HMI & Mobile Tooling**: Python (PyQt6, PyQtGraph, PySerial), C# (.NET 8, WPF, ScottPlot 5), Kotlin (Android Jetpack Compose, Coroutines)
- **Laboratory & Debug Tools**: Oscilloscope, Serial Port Monitor, Digital Multimeter (DMM)
- **Development Environment**: Git, Linux (Ubuntu, Raspberry Pi OS), VS Code, Visual Studio, Android Studio

---

## SELECTED PROJECTS

### Industrial BLE Configuration & OTA Tool (SensaTuner)
*Embedded Mobile Tool — Kotlin / BLE GATT / Bootloader Update*

- Developed an Android mobile tool in Kotlin (Jetpack Compose) for on-site PSoC 6 / 5LP sensor configuration and wireless OTA firmware updates via BLE GATT (MTU 247), replacing bulky laptop setups.
- Implemented `.cyacd` / `.cyacd2` firmware parsing and bootloader sequencing with automatic retry (up to 3 retries/row, 10 ms queue back-off), achieving 100% success across 150+ field OTA test cycles.
- Integrated real-time 3-axis vibration spectrum plots at 60 FPS to support field engineers.

---

### Real-Time Laser Monitoring Workbench (Hilltop MTS)
*Desktop Instrumentation — Python / PyQt / Sensor Interface*

- Built the desktop GUI in Python (`PyQt6`, `PyQtGraph`) for a 4-channel virtual oscilloscope monitoring laser stabilization at 60 FPS.
- Diagnosed UI sluggishness during continuous data streaming, improved chart responsiveness across 48-hour continuous test runs, and collaborated with the team on FPGA TCP control logic integration.

---

### Cellular IoT & PSoC 6 Firmware Validation (Sensaio)
*Embedded Firmware & Testing — C / C++ / UART AT Commands*

- Contributed to PSoC 6 firmware maintenance by adding helper routines, testing basic algorithm updates, and fixing minor firmware bugs.
- Executed end-to-end LTE-M / NB-IoT cellular modem validation over UART AT commands, resolving communication timeout and pin-mapping issues via serial logs and oscilloscope.
- Built Python helper scripts to automate repetitive AT-command test sequences on the hardware bench.

---

### Industrial Desktop HMI & Bench Test Utilities
*Test Tooling & Maintenance — C# WPF / Python / Serial DAQ*

- Maintained and stabilized C# WPF monitors and test fixtures across 25-channel 100 Hz binary UART DAQ (109-byte frames, 24h test runs), 1 Mbps cryogenic monitoring (200k+ points at 30 FPS, ~140 MB RAM), and dual-port 921.6k/1M baud PCB testing (< 45s test cycle across 500+ pilot runs).
- Fixed UI freezing from continuous serial updates, resolved COM port disconnect bugs, and built small bench utilities to speed up repetitive manual checks.

---

### Smart Water Meter & Edge AI Monitoring System
*Graduation Thesis — Edge AI / IoT — Scored 8.7/10*

- Built an offline edge-AI water meter reader on `ESP32-CAM` using an INT8-quantized CNN model (`TensorFlow Lite Micro`, `Embedded C++`) to recognize mechanical meter digits without cloud dependency.
- Transmitted digitized meter readings over `LoRa` and `MQTT` to a monitoring dashboard.
- Achieved ~98% digit recognition accuracy across 612 collected meter frames (1,757 labeled digits) under varied lighting conditions.

---

## EDUCATION

### Vietnam-Korea University of Information Technology and Communications (VKU)
*Aug 2021 – Apr 2026*  
Bachelor of Science in Information Technology — Major: IoT & Robotics — Da Nang, Vietnam  
**GPA**: 3.21 / 4.0 · **Graduation Thesis**: 8.7 / 10

---

## LANGUAGES

- **Vietnamese**: Native · **English**: VSTEP B2
