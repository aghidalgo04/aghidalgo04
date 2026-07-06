<div id="header" align="center">
  <img src="https://avatars.githubusercontent.com/u/252324167?v=4" width="150" style="border-radius: 50%;"/>
  <h1>Alejandro García Hidalgo</h1>
  <p><strong>Computer Engineer | FPGA & Embedded Systems</strong></p>
</div>

<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/alejandro-garcia-hidalgo/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Linkedin Badge"/>
  </a>
  <a href="https://github.com/aghidalgo04">
    <img src="https://img.shields.io/badge/Github-393838?style=for-the-badge&logo=github&logoColor=white" alt="Github Badge"/>
  </a>
  <a href="https://www.youtube.com/@aghidalgo04">
    <img src="https://img.shields.io/badge/YouTube-f54949?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  </a>
</div>

---

### Professional Summary

* **Education:** Computer Engineer graduated from **Universidad Politécnica de Madrid (UPM)**, with an international academic background via an Erasmus+ exchange at **AGH University of Krakow**, specializing in **Radiation Resistance of Electronic Systems** and Advanced Embedded Systems.
* **Technical Focus:** Digital Design (VHDL/Verilog), Digital Signal Processing (DSP) on FPGAs, and RTOS-based firmware development.
* **Experience:** Former **FPGA Engineer** at **RBZ Embedded Logics**. Experienced in SoC architectures (Zynq/MicroBlaze), AXI-to-Wishbone interconnects, and Zephyr RTOS connectivity solutions.

---

### Technical Stack

| Category | Technologies |
| --- | --- |
| **Hardware / RTL** | VHDL, Verilog, Vivado, Vitis, Zynq-7000, Artix-7, MicroBlaze |
| **Software / Firmware** | C, C++ (OOP), Python (NumPy, Matplotlib), Embedded C, Zephyr RTOS, ESP-IDF |
| **Protocols & Buses** | AXI4, Wishbone, SPI (custom FSM), I2C, UART, MQTT, CAN |
| **Design & Analysis** | KiCad (PCB Layout), Saleae Logic, SysML, MATLAB/Simulink |

---

### Featured Projects

#### [Real-Time 3D Vectorcardiography & ECG Analysis on FPGA](https://github.com/aghidalgo04/ECG_in_FPGA_Thesis)
* **Bachelor Thesis:** Designed and implemented a portable digital architecture on an **Artix-7 FPGA** for real-time 3D cardiac monitoring and autonomous pathology detection (Arrhythmia, Bradycardia, Tachycardia, Asystole, and Sudden Death risk).
* **DSP & RTL Design:** Developed a parallel processing pipeline in **VHDL** utilizing a **3D Wavelet Transform (*à trous* algorithm)** and adaptive state machines for precise QRS and T-wave delineation, heavily optimizing hardware resources via bit-shifting arithmetic.
* **Data Integrity:** Engineered a custom **SPI controller (FSM)** and a **majority voting logic (2-out-of-3)** to synchronize spatial axes and eliminate noise-induced false positives.
* **Telemetry:** Programmed an interactive **Python dashboard** to parse UART frames, rendering the raw signals, real-time medical alerts, and the 3D VCG loop dynamically.

#### [Gas Detection System - RTL Architecture](https://github.com/aghidalgo04/SistemaDeteccionGasesHogar)
* Modular VHDL design for **Artix-7** utilizing the **Xilinx XADC IP Core** for real-time monitoring of CH4 and CO2.
* Implementation of the **Double-Dabble algorithm** for binary-to-BCD conversion and analog signal conditioning.

#### [Smart Lamp - Embedded Systems](https://github.com/aghidalgo04/SmartLamp)
* Environmental control system based on the **PIC16F886** microcontroller.
* Implementation of a modular **HAL in C**, a robust **UART telemetry protocol** with **CRC checksums**, and an interrupt-driven FSM.
* Full **PCB design** in KiCad based on a SysML system architecture.

#### [Smart Hydroponic NIR Monitor](https://github.com/aghidalgo04/DistribuidorFitonutrientesNPK)
* IoT sensing node for nutrient analysis (N-P-K) using **18-channel NIR spectroscopy** and Electroconductivity sensing.
* Firmware developed in **C/ESP-IDF** with an **MQTT telemetry pipeline** and **OTA (Over-The-Air)** update capabilities.

---

### Contact Information
* **Email:** aghidalgo04@gmail.com
* **LinkedIn:** [alejandro-garcia-hidalgo](https://www.linkedin.com/in/alejandro-garcia-hidalgo/)
