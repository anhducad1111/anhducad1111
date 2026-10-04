# NGUYEN ANH DUC

**HMI / Embedded / IoT Engineer**

📍 Ngu Hanh Son, Da Nang  
📞 0943079599  
📧 [anhducad1111@gmail.com](mailto:anhducad1111@gmail.com)  
🌐 [anhducad1111.github.io](https://anhducad1111.github.io)  
🔗 [GitHub: anhducad1111](https://github.com/anhducad1111)  
🔗 [LinkedIn: anhducad1111](https://linkedin.com/in/anhducad1111)  

---

## SUMMARY

HMI / Embedded Systems Engineer with 1+ year of hands-on experience developing real-time instrumentation, data acquisition, and hardware-integrated software. Experienced in C# WPF, Python/PyQt6, high-speed binary serial communication, real-time visualization, and hardware/software integration. Background in embedded connectivity including BLE GATT, LTE-M/NB-IoT, and UART. Currently on international secondment as Junior Firmware Developer with THESIS PTE LTD (Singapore), expanding into ARM Cortex-M firmware development.

---

## WORK EXPERIENCE

### Junior Firmware Developer | THESIS PTE LTD — Singapore (Secondment)
*Sep 2026 – Present*

- Developing and maintaining embedded firmware in C/C++ for ARM Cortex-M platforms under senior engineer guidance.
- Working with peripheral interfaces including UART, SPI, I²C, GPIO, and ADC across bare-metal and RTOS-based systems.
- Supporting hardware bring-up, firmware/PCB integration, and debugging using J-Link, SWD, and serial diagnostics.
- Investigating firmware issues, participating in code reviews, and maintaining technical documentation.

---

### HMI / Embedded / IoT Engineer | Enable Startup — Da Nang
*Jun 2025 – Present*

- Architected a multi-process scientific control workbench in Python (PyQt6, PyQtGraph) for precision optical metrology; decoupled FPGA data acquisition into a dedicated OS process via IPC queue, implemented phase-sensitive demodulation with 4th-order SOS Butterworth filtering, and designed a closed-loop auto-lock state machine achieving sub-millivolt zero-crossing convergence while maintaining 60 FPS OpenGL rendering.
- Designed and implemented high-performance desktop HMI applications in C# .NET 8 WPF (MVVM + ScottPlot 5) for multi-channel scientific sensor acquisition over 1 Mbps binary UART links; engineered pre-allocated flat buffer pipelines sustaining 200,000-point real-time visualization at 30 FPS during 48-hour continuous soak testing.
- Implemented a 25-channel binary serial DAQ system with a circular ring buffer parser resolving byte-boundary misalignment at 100 Hz, paired with an automated 5-step in-situ polynomial calibration wizard.
- Developed application-level firmware for a PSoC6 host controller interfacing an nRF9160 LTE-M/NB-IoT modem via AT commands over UART; diagnosed UART buffer desynchronization and pin-mapping conflicts through serial-log inspection and oscilloscope signal tracing.
- Designed Python host application integrating a 3-axis CNC motion controller via native C-DLL (`ctypes`) with explicit struct alignment; engineered continuous fly-by rastering achieving 7× scan speedup (500 × 500 volumetric grid in < 22 minutes).
- Implemented a concurrent dual-port serial ATE system (921,600 baud and 1,000,000 baud simultaneously) with WMI-based COM port auto-discovery; reduced PCB factory functional test cycle time from 10 minutes to under 45 seconds.
- Collaborated with hardware engineers and Singapore-based research partners on system integration, hardware-software validation, and technical requirements translation.

---

## TECHNICAL SKILLS

**Embedded & Firmware**  
C / C++ · ARM Cortex-M · Nordic nRF · STM32 · PSoC 6 / 5LP · ESP32  
Bare-metal · FreeRTOS · UART · SPI · I²C · GPIO · ADC

**Communication & Protocols**  
BLE GATT Client · LTE-M / NB-IoT (AT Commands) · MQTT · LoRa / LoRaWAN  
TCP/IP · SCPI over TCP · Binary Custom Framing · CRC16

**HMI & Desktop Software**  
Python (PyQt6 · PyQtGraph · SciPy · NumPy · ctypes) · C# (.NET 8 · WPF · MVVM)  
ScottPlot 5 · Real-Time Visualization · Multiprocessing IPC · Producer-Consumer Pipelines

**Debug & Test Equipment**  
J-Link (Segger) · SWD / JTAG · Oscilloscope · Logic Analyzer (Saleae) · Serial Port Monitor  
Wireshark · dotMemory · Visual Studio Diagnostic Tools

**Tools & Platforms**  
Git · Linux (Ubuntu · Raspberry Pi OS) · CMake  
VS Code · Visual Studio 2022 · Android Studio · Kotlin 2.0

---

## PROJECTS

### Real-Time Laser Frequency Stabilization Workbench
*Scientific Instrumentation — FPGA / DSP / Closed-Loop Control*

- Implemented a real-time 4th-order SOS Butterworth filtering and phase-sensitive demodulation pipeline with persistent filter state across streaming chunks; designed a deterministic auto-lock state machine with zero-crossing capture, 2-stage anti-windup, and actuator rail saturation detection.
- Achieved 60 FPS real-time 4-channel oscilloscope rendering and < 1 mV zero-crossing convergence window.
- `PyQt6` · `PyQtGraph (OpenGL)` · `SciPy / NumPy` · `Multiprocessing IPC` · `Digital PID`

---

### Industrial BLE OTA & Field Diagnostic Tool
*Embedded Mobile Tool — Kotlin / BLE GATT / Bootloader Protocol*

- Ported the proprietary Cypress DFU protocol from legacy Python into an asynchronous Kotlin Coroutines engine on Android BLE GATT, enabling wireless field upgrades for PSoC 6 dual-core (`.cyacd2`) and PSoC 5LP (`.cyacd`) devices without transport laptops.
- Engineered binary container parsers with table-driven CRC-32C (Castagnoli, `0x82F63B78`) calculation and an 8-stage DFU state machine; implemented dual transmission modes (Safe Mode with chunk-level ACKs vs. Fast Mode with unacknowledged writes and GATT queue-saturation back-off).
- Achieved 100% flash success rate across 150+ field test cycles under 2.4 GHz factory interference, while integrating real-time 3-axis vibration FFT/PSD spectrum streaming with ISO 10816 condition monitoring overlays at 60 FPS.
- `Kotlin 2.0` · `Jetpack Compose` · `Android BLE GATT` · `Cypress DFU Protocol` · `Coroutines / StateFlow` · `PSoC 6 / 5LP`

---

### Smart Water Meter & Edge AI Monitoring System
*Graduation Thesis — Edge AI / IoT — Scored 8.7/10*

- Designed an offline edge-AI pipeline for water meter digit recognition: ROI-based image preprocessing, INT8-quantized CNN inference on ESP32-CAM, and LoRa/MQTT uplink for remote consumption reporting.
- Achieved ~98% test accuracy on a self-collected dataset of 612 frames with 1,757 labeled digits.
- `ESP32-CAM` · `TensorFlow Lite Micro` · `INT8 Quantization` · `LoRa` · `MQTT`

---

## EDUCATION

### Vietnam-Korea University of Information Technology and Communications (VKU)
*Aug 2021 – Apr 2026*  
Bachelor of Science in Information Technology — Major: IoT & Robotics  
**GPA**: 3.21 / 4.0 · **Thesis**: 8.7 / 10

---

## LANGUAGE

- **English**: VSTEP B2
