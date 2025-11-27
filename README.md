# Hi, I'm Laingam

Embedded Systems & Edge AI Engineer  
I build real-world intelligence on microcontrollers.

I design end-to-end embedded solutions where ML inference runs directly on MCU hardware.  
My focus is on DMA-driven sensor pipelines, low-power firmware, and real-time decision systems without cloud dependency.

---

## What I Work On

• Embedded C/C++ development on ARM Cortex-M (STM32, TI)
• Driver-level peripheral integration (I2C, SPI, UART, ADC, Timers)
• Low-power system design (sleep modes, event-driven wakeups)
• Real-time signal processing (IMU, vibration, audio)
• TinyML deployment (feature extraction → model → inference)
• IoT hardware (GPS, GSM, MQTT, sensor gateways)

---

## Highlighted Projects

Embedded Human Activity Recognition - STM32 + TinyML  
Real-time motion classification (Idle / Walk / Run) deployed fully offline on a microcontroller.  
DMA-based IMU pipeline → window segmentation → physics features → SVM inference.  
Memory footprint: < 20 KB Flash, ~2 KB RAM. MCU sleep > 90%.

GPS/GSM Anti-Theft Tracker - STM32 L432KC  
Custom embedded system using Neo-6M GPS + SIM800L GSM for unauthorized vehicle detection.  
Optimized GPS lock time and implemented robust AT command pipeline for reliable SMS alerts.  
Delivered as a working prototype to a paid client.

Wildlife Acoustic Edge ML Device  
Microphone-based system to detect environmental threats (chainsaw, vehicles, predator presence).  
Acoustic feature extraction + offline inference on STM32L4 for remote, zero-connectivity use cases.

Predictive Maintenance System  
Vibration analytics using ADC + DMA for rotating machinery.  
Extracted RMS/variance/peak metrics and implemented on-device anomaly detection logic in real-time.

---

## Core Competencies

Embedded Engineering  
• STM32 HAL/LL, TI SimpleLink/Tiva-C  
• FreeRTOS / TI-RTOS  
• DMA, ISRs, circular buffering  
• Sensor fusion, event-driven state machines

Hardware ↔ Firmware Integration  
• IMU (LSM6DSL), MEMS microphones  
• GPS (Neo-6M), GSM (SIM800L)  
• OLED / SPI peripherals  
• Driver development from scratch

Edge ML Workflow  
• Physics-based feature extraction (variance, FFT, RMS)  
• Model compression + deployment  
• Offline inference under memory constraints  
• Power & performance optimizations

---

## Engineering Mindset

I don’t build demos.  
I build working embedded devices under real constraints:

– Low RAM / Flash  
– Power budget  
– Sensor noise / drift  
– Network instability  
– Offline inference  
– Hardware faults

If it runs on a microcontroller and makes a decision at the edge,  
I’m interested.

---


#### 🔗 Connect with Me
* [LinkedIn Profile](www.linkedin.com/in/laingam98) 
* Email: laingam438@gmail.com
