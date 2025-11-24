# Harrison Williams  
**Electrical & Computer Engineering @ UT Austin**  
Hardware Track — Electronics & Integrated Circuits  

[GitHub](https://github.com/harrison-wms) • [LinkedIn](https://www.linkedin.com/in/HarrisonWilliamsECE) • [Email](mailto:Harrison.Williams@utexas.edu)

---

## About Me

I'm an Electrical and Computer Engineering student at The University of Texas at Austin, focusing on
**digital design, analog/mixed-signal electronics, DSP, and semiconductor validation**. My coursework
and projects span the full hardware stack—from circuit-level analysis and semiconductor behavior to
RTL logic design, embedded systems, and real-time signal processing.

I’ve completed a strong set of hardware-oriented ECE courses, including Introduction to Electrical and Computer
Engineering (ECE 302), Introduction to Computing (ECE 306), Software Design and Implementation I (ECE 312),
Linear Systems and Signals (ECE 313), Digital Logic Design with Verilog/FPGA (ECE 316), Embedded
Systems on MSPM0 (ECE 319K), Electromagnetic Engineering (ECE 325), Probability & Random
Processes (ECE 351K), and Circuit Theory (ECE 411). These courses have given me a foundation in
circuit analysis, device behavior, HDL-based digital design, DSP fundamentals, embedded development,
and mathematical tools used across hardware engineering.

By Summer 2026, I will have also completed **Fundamentals of Electronic Circuits I LAB (ECE 438),
Real-Time Digital Signal Processing LAB (ECE 445S), and Digital System Design Using HDL (ECE 460M)**,
further strengthening my background in analog electronics, embedded real-time systems, and advanced
digital logic/RTL design.

My hands-on work includes FPGA modules (RCA/CLA adders, timing systems), embedded game
development on ARM microcontrollers, octave-spaced FIR filter banks and DSP pipelines in MATLAB,
custom Li-ion battery pack design (8s4p–12s8p), 3D printer electronics modifications, and building
high-current custom electric longboards.

I’m especially interested in roles involving:

- **Semiconductor validation** (digital and mixed-signal)  
- **Digital logic and RTL design** (FPGA/ASIC)  
- **Analog and mixed-signal circuit design**  
- **Hardware testing, bring-up, and characterization**  
- **System-level hardware integration**  
- **DSP and signal-chain engineering**

I enjoy designing measurable, reliable hardware systems and working at the intersection of digital logic,
analog behavior, embedded computation, and physical electronics.

---

## Featured Projects

---

### 🔋 1. High-Voltage Li-Ion Battery Packs (10s3p → 12s8p)
**Skills:** nickel strip layout, spot welding, BMS wiring, fuse selection, safety design, enclosure integration  
**Tools:** Spot welder, soldering station, 3D printing, multimeter,  CAD

Built multiple custom lithium-ion battery packs ranging from 10s3p to 12s8p using 18650 and 21700 cells.  
Parallel groups were welded using nickel strip, and high-current series wiring was sized to handle elevated discharge currents safely.

Each pack included:
- Spot-welded nickel interconnects for parallel grouping  
- Series wiring for high-current discharge  
- BMS integration for balancing and protection  
- Inline fusing and safe charge/discharge leads  
- Custom 3D-printed enclosures for mechanical structure and electrical isolation  

Currently developing **post-build CAD models** to visualize optimized pack geometries, spacing, and future redesigns.

[Repo Coming Soon]

---

### 🧩 2. FPGA Digital Timer & RCA/CLA Arithmetic Modules (ECE 316)
**Skills:** Verilog, HLSM/FSM design, arithmetic logic, timing analysis, FPGA prototyping  
**Tools:** Xilinx Vivado, Basys3 FPGA

Designed and implemented key digital modules for a programmable timer system, including:
- **4-bit Ripple-Carry Adder (RCA)**
- **4-bit Carry-Lookahead Adder (CLA)**
- **Counters and programmable timing logic**
- **Time-multiplexed display drivers**
- **Finite-state controllers for real-time operation**

Performed synthesis-based analysis comparing **propagation delay**, **critical path**, and **resource
utilization** between RCA and CLA architectures. Integrated the adders into a larger FPGA-based timer
to demonstrate practical tradeoffs between area and speed in digital design.

Validated functionality on the Basys3 FPGA using real-time I/O, event-driven logic, and timing-safe RTL.

[Repo Coming Soon]

---

### 👾 3. Space Invaders on MSPM0 (ECE 319K)
**Skills:** C, ARM assembly, interrupts, ADC, DAC audio synthesis  
**Tools:** Code Composer Studio, MSPM0G3507 LaunchPad

Developed a real-time Space Invaders–style game with:
- Interrupt-driven movement and rendering  
- ADC joystick input  
- DAC audio generation  
- Collision detection and timer-based gameplay loops  

Demonstrated an embedded game engine built entirely on low-level I/O.

[Repo Coming Soon]

---

### 🎧 4. Octave-Spaced FIR Filter Bank (ECE 313)
**Skills:** multirate DSP, FIR filter design, reconstruction, PSNR/SNR analysis  
**Tools:** MATLAB

Built octave-spaced FIR analysis and synthesis filter banks and performed:
- Downsampling/upsampling  
- Multirate filtering  
- Audio compression effects  
- Spectral and time-domain analysis  

Implemented an image → audio → image transformation pipeline demonstrating reconstruction fidelity.

[Repo Coming Soon]

---

### 🎼 5. Audio Signal → Image Transformation Pipeline (ECE 313)
**Skills:** Fourier transforms, magnitude/phase decomposition, real-valued signal reconstruction  
**Tools:** MATLAB

Implemented a full pipeline that converts an audio signal into an image representation and then
reconstructs the original signal using frequency-domain techniques.

Pipeline included:
- Segmenting audio into overlapping windows  
- Computing magnitude and phase spectra via FFT  
- Assembling magnitudes into an image matrix  
- Reversing the process to reconstruct the audio  
- Evaluating fidelity through SNR/PSNR and spectrogram comparison  

This project demonstrated practical applications of Fourier analysis, block processing, and signal
representation transformations in MATLAB.

[Repo Coming Soon]

---

### 🖨️ 6. 3D Printer Upgrades & Laser Engraver Conversion
**Skills:** firmware tuning, motor driver configuration, PWM laser control, mechanical design  
**Tools:** Marlin firmware, TMC2209 drivers, LightBurn, 3D printing

Upgraded a CR-10 clone printer with:
- SKR Mini control board  
- TMC2209 stepper drivers  
- Frame stiffening and linear rails  
- Firmware modifications for improved motion accuracy  

Converted the printer into a diode-laser engraver by repurposing PWM fan outputs for laser modulation.

[Repo Coming Soon]

---

## Upcoming Projects

### ⚡ VESC Repair & Gate-Driver Replacement (Winter 2025)
Diagnosing and restoring damaged VESC motor controllers, including:
- DRV gate-driver SMD removal and replacement  
- Hot-air reflow and inspection  
- Firmware recovery and SWD reflashing via ST-LINK  

This project will document common VESC failure modes and practical repair techniques for high-power ESCs.


## Contact

📧 **Harrison.Williams@utexas.edu**  
🔗 [LinkedIn](https://www.linkedin.com/in/HarrisonWilliamsECE)  
🔗 [GitHub](https://github.com/harrison-wms)

---

### (More project pages coming soon)
