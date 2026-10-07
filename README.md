Safe Clock-Gated Low-Power DSP Block Using Verilog HDL 📌 Overview

A Verilog HDL-based low-power DSP block designed and verified using Xilinx Vivado. The project demonstrates safe clock-enable operation to reduce unnecessary switching activity and compares it with unsafe clock gating.

⚙️ Working Principle
Input Data
    ↓
DSP Processing
    ↓
Enable Control
    ↓
Output Data

When Enable = 1, the DSP processes the input data.
When Enable = 0, the output is held to reduce unnecessary switching.

🧩 Main Modules
dsp_block_original.v – Original DSP block
safe_clock_gating.v – Safe clock-enable implementation
unsafe_clock_gating.v – Unsafe clock-gating demonstration
dsp_top.v – Top-level module
tb_safe_clock_gated_dsp.v – Testbench
🛠️ Tools & Technologies
Verilog HDL
Xilinx Vivado
RTL Design
Digital Signal Processing
Low-Power Design
Waveform Simulation
📊 Applications
Low-power DSP systems
FPGA-based designs
Embedded systems
IoT devices
Power-efficient digital circuits
🚀 Future Scope
FPGA hardware implementation
Detailed power analysis
Larger DSP processing
Real-time signal processing
Improved power optimization
👨‍💻 Project Outcome

Successfully designed and verified a safe clock-enable based low-power DSP block using Verilog HDL and Xilinx Vivado, demonstrating reduced unnecessary switching while maintaining correct functionality.
