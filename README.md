## 🛠️ Advanced Engineering Features

### 🔍 Smart Optical System
* **Dynamic Autofocus:** Real-time distance measurement using ToF sensors to drive a NEMA 8 stepper, achieving perfect focus for macro photography.
* **Elasticity Compensation Algorithm:** Custom software correction for belt-driven actuators, mitigating non-linear mechanical errors in custom-made transmissions.

### 🧠 Computer Vision Pipeline
* **Hierarchical Scanning:** 720p Sweep Mode for ROI (Region of Interest) detection and 4K Analysis Mode for micro-inspection.
* **Multiclass AI Model:** Custom dataset trained to identify components, read serial numbers (OCR), and detect soldering defects (cracks, bridges, or missing solder).

### ⚙️ Hardware Architecture
* **Main Controller:** STM32F4 (Handling IK and real-time motion).
* **Distributed Sensing:** ESP32U via UART for joint telemetry (AS5600 encoders).
* **Driver Stage:** Hybrid setup with TB6600, DRV8825, and TMC2130 for silent, high-precision movement.

