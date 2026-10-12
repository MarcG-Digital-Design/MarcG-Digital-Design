<!-- Header avec basculement automatique Sombre/Clair -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=E5E7EB&height=150&text=">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=000008&height=150&text=Digital+Systems+Engineer" width="100%">
  </picture>
</p>

<!-- Mon message perso avec ajustement selon le theme blanc/noir -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&size=35&pause=1000&color=E0DADA&width=435&lines=Hello+it's+Marc;Welcome+on+my+GitHub">
  <img alt="Typing SVG" src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=35&pause=1000&color=000000&width=435&lines=Hello+it's+Marc;Welcome+on+my+GitHub">
</picture>

I am a **Digital Systems Engineer** passionate about FPGA design, hardware architecture, and embedded systems.

> 🚧 *Completed projects are progressively being cleaned up and documented, while new FPGA/SoC projects are actively under development.*

---

### 🛠 Technical Skills

* **Hardware Description:** VHDL, SystemVerilog
* **Design Workflow:** RTL Synthesis, Timing Analysis, Place & Route, Hardware Implementation
* **FPGA/SoC Design:** AMD/Xilinx Vivado, Intel/Altera Quartus Prime
* **Embedded Systems:** Microcontrollers, C/C++, Embedded Linux
* **Tools & Versioning:** QuestaSim, ModelSim, Tcl Scripting

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,gitlab,linux,vim,vscode,py,matlab,c,cpp,arduino" />
  </a>
</p>

---

### 💻 Projects

*Below is a selection of my key projects, demonstrating the full design cycle from RTL development to FPGA/SoC integration and real-time hardware validation.*

* **[VGA Video Controller -- DE-10 LITE QUARTUS](https://github.com/MarcG-Digital-Design/fpga-vga-controller)** ![Status](https://img.shields.io/badge/status-ready-brightgreen) - A custom VGA controller implemented on FPGA to display a static image stored in internal block RAM.

* **[FPGA Digital Stopwatch -- DE-10 LITE MAX10 QUARTUS](https://github.com/MarcG-Digital-Design/fpga-stopwatch)** ![Status](https://img.shields.io/badge/status-ready-brightgreen) - A feature-rich digital stopwatch featuring Play/Pause/Reset functionality, implemented with a **Double Dabble algorithm** for efficient BCD conversion and multiplexed 7-segment display control.

* **[Real-time FPGA Signal Processing -- ZYBO ZYNQ-7000 VIVADO](https://github.com/MarcG-Digital-Design/fpga-signal-processing)** ![Status](https://img.shields.io/badge/status-in_progress-yellow) - Development of a low-pass filter implemented on FPGA.
  * **Full Design Cycle:** Theoretical analysis, coefficient calculation, and MATLAB simulation.
  * **Implementation:** RTL design, SPI interface development for high-speed ADC/DAC communication.
  * **Validation:** Real-time signal processing and performance verification.

* **FPGA/SoC Signal Processing -- ZYBO ZYNQ-7000 VIVADO** ![Status](https://img.shields.io/badge/status-in_progress-orange) - Hardware/software co-design experiment based on the existing real-time FPGA signal-processing project.
  * **Soft-core / Processor:** Handles data acquisition, control, and output data transfer.
  * **FPGA Processing:** The FIR filter remains implemented in dedicated RTL hardware for deterministic and parallel processing.
  * **HW/SW Co-design:** Evaluation of the partitioning between software-managed data flow and FPGA-based computation.
  * **Performance Analysis:** Comparison of latency, throughput, FPGA resource usage, and power consumption.
 
* **Multi-Clock FPGA Streaming System -- DE-10 LITE MAX10 QUARTUS** ![Status](https://img.shields.io/badge/status-in_progress-orange) - Development of a multi-clock RTL processing architecture focused on robust digital design, automated verification, Clock Domain Crossing, and timing closure.
  * **RTL Architecture:** Streaming datapath with multiple clock domains, FIFO-based buffering, and pipelined processing.
  * **Clock Domain Crossing:** Metastability analysis, two-flop synchronizers, asynchronous FIFO design, and Gray-code pointer synchronization.
  * **Verification:** Self-checking VHDL testbenches and automated Python/cocotb verification using reference-model comparison.
  * **Timing Analysis:** SDC constraints, setup/hold analysis, WNS/TNS, critical-path investigation, and timing closure through pipelining.
  * **Implementation & Debug:** FPGA resource analysis, Place & Route inspection, and on-board debugging using Intel SignalTap.

---

*Looking for new challenges in digital design, FPGA/SoC development, hardware verification, and embedded systems!*

<!-- Footer avec basculement automatique Sombre/Clair -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=E5E7EB&height=150&section=footer">
    <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=000008&height=150&section=footer">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=E5E7EB&height=150&section=footer" width="100%">
  </picture>
</p>
