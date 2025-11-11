Hi, I'm Nirrbhay Raghavan  

I’m a Computer Engineering student at **Purdue University (Class of 2027)** passionate about **end-to-end system design** — from PCB layout and embedded firmware to FPGA and AI-driven software.  
My work bridges **hardware, firmware, and computation**, with a focus on building high-performance, real-time systems.


Featured Projects

Portable Handheld Gaming Console  
Initiated this project by designing a **custom two-layer Raspberry Pi Compute Module 4 (CM4) carrier board**, integrating dual displays, I²S audio DAC, and USB-C PD circuitry.  
Started development with **Jetson Nano prototypes** for architecture testing and schematic validation before migrating to the CM4 platform, optimizing connector layout, signal routing, and thermal performance.  
Currently developing **C/C++ firmware** for display, input, and audio control, focusing on stable Linux bring-up and sub-10 ms I/O response.  
Validated EMI and timing integrity using oscilloscopes and logic analyzers to ensure system-level reliability.  
Planned next phase includes **porting the design to a CM5-based carrier board (Adaxa)** and building **embedded AI utilities** in C++ and Python for intelligent diagnostics, performance monitoring, and adaptive firmware optimization.  

---

ESP32 HTTP Photo Server  
Designed and assembled a **custom ESP32 board** with USB-C power, TFT display, and MicroSD storage using KiCad.  
Developed **FreeRTOS-based firmware** in C++ for concurrent image capture, data buffering, and Wi-Fi transmission.  
Implemented asynchronous task scheduling and memory optimization for efficient power usage and near real-time streaming.  
Validated throughput and latency improvements via logic analysis and benchmarking.  
This project demonstrates hardware-software co-design for IoT devices and edge data processing.

---

Real-Time Sensor Node (Embedded + FPGA Co-Design)  
Developed a **real-time sensor node platform** combining embedded and digital design techniques for sub-10 ms response latency.  
On the embedded side, implemented **FreeRTOS multitasking firmware** on ESP32 for concurrent sensor, communication, and control tasks.  
In parallel, designed a **Verilog-based UART and sensor interface module**, co-simulated with embedded firmware to verify data timing and determinism.  
Validated system synchronization using oscilloscopes and HDL simulation tools, integrating hardware and firmware for real-time operation.  
This unified project blends embedded firmware, digital logic design, and timing verification — bridging the gap between MCU-level control and FPGA signal handling.

---

Microcontroller Weather Station  
Created a **sensor-hat PCB** for an ARM Proton board to monitor temperature, humidity, and pressure.  
Programmed in **C and Assembly** to interface with GPIO, SPI, and UART peripherals for live sensor acquisition.  
Integrated real-time data display and serial telemetry parser with interrupt-driven routines for reliable communication.  
This project exemplifies embedded control, circuit integration, and data communication at the microcontroller level.

---

Intelligent OCR Pipeline  
Engineered a **multimodal OCR system** using Donut, LayoutLMv3, and DocTR to extract structured data from invoices.  
Integrated the workflow into **Flask APIs and AWS Lambda**, linked to a PostgreSQL backend with fuzzy matching logic.  
Optimized inference pipelines for 89% field-level accuracy while maintaining scalability and low-latency performance.  
This project bridges high-level AI model development with embedded deployment, demonstrating software efficiency and real-world integration.

---

