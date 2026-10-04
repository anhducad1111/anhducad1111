# NGUYEN ANH DUC

**HMI / Embedded Systems / IoT Engineer**

📍 Da Nang, Vietnam  
📞 (+84) 943 079 599  
📧 [anhducad1111@gmail.com](mailto:anhducad1111@gmail.com)  
🌐 [Portfolio: anhducad1111.github.io](https://anhducad1111.github.io)  
🔗 [GitHub: github.com/anhducad1111](https://github.com/anhducad1111)  
🔗 [LinkedIn: linkedin.com/in/anhducad1111](https://linkedin.com/in/anhducad1111)  

---

## SUMMARY

HMI & Embedded Systems Engineer with 1+ year of experience building real-time scientific instrumentation, data acquisition pipelines, and hardware-integrated desktop software. Skilled in C# WPF, Python/PyQt6, high-speed binary UART, and BLE GATT protocol integration. Currently on international secondment as Junior Firmware Developer with THESIS PTE LTD (Singapore), executing ARM Cortex-M firmware bring-up and peripheral driver integration under senior guidance.

---

## WORK EXPERIENCE

### Junior Firmware Developer | THESIS PTE LTD — Singapore (Secondment)
*Sep 2026 – Present*

- Developing ARM Cortex-M embedded firmware in C/C++ under senior engineer guidance, validating peripheral drivers (UART, SPI, I²C, GPIO, ADC) across bare-metal systems.
- Executed hardware bring-up and firmware/PCB validation for PSoC 6 and nRF9160 evaluation platforms using Segger J-Link, SWD, and Saleae logic analyzers.
- Diagnosed UART framing errors and buffer desynchronization during low-level AT command modem integration through serial log traces and oscilloscope signal verification.

---

### HMI / Embedded / IoT Engineer | Enable Startup — Da Nang, Vietnam
*Jun 2025 – Present (Concurrent with THESIS Secondment)*

- **Scientific HMI Workbench (PyQt6 / FPGA)**: Architected a multi-process control workbench for optical metrology; decoupled FPGA ingestion into dedicated OS process via IPC queues, implemented 4th-order SOS Butterworth IIR filtering with chunk state persistence, and designed a closed-loop auto-lock PID state machine achieving < 1 mV zero-crossing convergence at 60 FPS OpenGL rendering.
- **High-Speed Sensor DAQ (C# WPF / ScottPlot 5)**: Designed desktop HMI applications in .NET 8 WPF over 1 Mbps binary UART; engineered pre-allocated flat buffer pipelines sustaining 200,000-point real-time plots at 30 FPS during 48-hour continuous soak tests.
- **Multi-Channel DAQ Parser**: Built a 25-channel binary serial parser with circular ring buffer resolving 100 Hz byte-boundary misalignment, integrated with an in-situ 5-step polynomial calibration wizard.
- **Ultrasound Motion Controller**: Integrated 3-axis CNC gantry via native C-DLL (`ctypes`) with struct ABI alignment; engineered continuous fly-by rastering achieving 7× scan speedup (500 × 500 volumetric grid in < 22 minutes).
- **Automated PCB Functional Tester**: Implemented a concurrent dual-port serial ATE system (921,600 & 1,000,000 baud) with WMI COM auto-discovery, reducing factory test cycle time from 10 minutes to under 45 seconds.

---

## TECHNICAL SKILLS

**HMI & Desktop Software (Proficient)**  
Python (PyQt6, PyQtGraph, SciPy, NumPy, ctypes) · C# (.NET 8, WPF, MVVM) · ScottPlot 5 · Multiprocessing IPC · Real-Time Visualization

**Communication & Protocols (Proficient)**  
BLE GATT Client · UART (up to 1 Mbps) · Binary Custom Framing · SCPI over TCP · CRC16 / CRC32C · AT Commands

**Embedded Firmware & Debug (Working Knowledge)**  
ARM Cortex-M · PSoC 6 / 5LP · Nordic nRF9160 · Bare-metal C/C++ · UART / SPI / I²C / GPIO / ADC · J-Link (SWD) · Saleae Logic Analyzer · Oscilloscope

**Tools & Platforms**  
Git · Linux (Ubuntu) · CMake · VS Code · Visual Studio 2022 · Android Studio · Kotlin 2.0

---

## PROJECTS

### Industrial BLE OTA & Field Diagnostic Tool
*Embedded Mobile Tool — Kotlin / BLE GATT / Bootloader Protocol*

- Ported Cypress DFU protocol from Python to asynchronous Kotlin Coroutines on Android BLE GATT, enabling wireless field upgrades for PSoC 6 (`.cyacd2`) and PSoC 5LP (`.cyacd`) devices without transport laptops.
- Engineered binary container parsers with table-driven CRC-32C Castagnoli (`0x82F63B78`) and an 8-stage DFU state machine featuring Safe Mode (chunk ACKs) and Fast Mode (unacknowledged writes with GATT queue flow control).
- Achieved 100% flash success rate across 150+ field test cycles under 2.4 GHz factory interference, while rendering live 3-axis vibration FFT/PSD spectrums with ISO 10816 overlays at 60 FPS.
- `Kotlin 2.0` · `Jetpack Compose` · `Android BLE GATT` · `Cypress DFU Protocol` · `Coroutines` · `PSoC 6 / 5LP`

---

### Smart Water Meter & Edge AI Monitoring System
*Graduation Thesis — Edge AI / IoT*

- Designed an offline edge-AI pipeline for water meter digit recognition: ROI preprocessing, INT8-quantized CNN inference (TensorFlow Lite Micro) on ESP32-CAM (RAM < 290 KB, latency < 180 ms), and LoRa/MQTT uplink for remote consumption reporting.
- Achieved ~98% test accuracy on a self-collected dataset of 612 frames (1,757 labeled digits).
- `ESP32-CAM` · `TensorFlow Lite Micro` · `INT8 Quantization` · `LoRa` · `MQTT`

---

## EDUCATION

### Vietnam-Korea University of Information Technology and Communications (VKU)
*Aug 2021 – Apr 2026*  
Bachelor of Science in Information Technology (Major: IoT & Robotics)  
**GPA**: 3.21 / 4.0 · **Graduation Thesis**: 8.7 / 10

---

## LANGUAGE & CERTIFICATION

- **English**: VSTEP B2 (Daily technical documentation & international collaboration with Singapore team)
