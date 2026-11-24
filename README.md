<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,35:30000a,65:850018,100:ff003c&height=250&section=header&text=Yahir%20Arreola&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Software%20is%20temporary.%20Silicon%20is%20eternal.&descAlignY=56&descSize=18"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=1000&color=FF003C&center=true&vCenter=true&width=900&lines=Software+is+temporary.+Silicon+is+eternal.;Building+intelligence+into+silicon.;From+transistors+to+processors.;Breaking+GPUs+to+understand+them.;Engineering+beyond+the+abstraction+layer." />

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-850018?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yahir-arreola)

</div>

---

## 01 // WHOAMI

```yaml
name: Yahir Arreola
school: University of Texas at El Paso
major: Computer Engineering
minor: Mathematics
graduation: May 2027
planned_next_step: M.S. in Computer Engineering

focus:
  - FPGA & RTL Design
  - Computer Architecture
  - Embedded Systems
  - Hardware Acceleration
  - Digital IC / VLSI
  - GPU Reliability

philosophy: "Software is temporary. Silicon is eternal."
```

Computer Engineering student focused on the layer beneath software —  
where logic becomes hardware, timing becomes reality, and performance is built one clock cycle at a time.

I’m especially interested in **FPGA design, processor architecture, embedded systems, and hardware acceleration**, with projects ranging from **custom digital systems** to **real-time intelligent hardware**.

---

## 02 // FEATURED PROJECTS

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d0d0d,100:8b001c&height=70&section=header&text=Featured%20Builds&fontSize=28&fontColor=ffffff"/>

</div>

---

## ⚠ Senior Design — FPGA Emergency Keyword Spotting System

<div align="center">

![FPGA](https://img.shields.io/badge/FPGA-Basys_3-850018?style=for-the-badge)
![Verilog](https://img.shields.io/badge/RTL-Verilog-171717?style=for-the-badge)
![DSP](https://img.shields.io/badge/Signal_Processing-DSP-850018?style=for-the-badge)
![Neural Net](https://img.shields.io/badge/Model-DS--CNN-171717?style=for-the-badge)
![RISC-V](https://img.shields.io/badge/Control-RISC--V-850018?style=for-the-badge)

</div>

### Mission
Building an **offline, real-time emergency keyword spotting system** that detects words like **“help”** and **“emergency”** using an FPGA-based neural network accelerator.

### System Graphic
```text
 ┌─────────────┐    ┌───────────────┐    ┌───────────────────┐    ┌────────────────────┐    ┌─────────────┐
 │ Microphone  │ -> │ Analog Front  │ -> │ DSP Feature Block │ -> │ DS-CNN Accelerator │ -> │ Alert Logic │
 │   Input     │    │     End       │    │ FFT / Mel / Frame │    │   INT8 Inference   │    │ / Response  │
 └─────────────┘    └───────────────┘    └───────────────────┘    └────────────────────┘    └─────────────┘
```

### Why it’s cool
- Hardware-accelerated **keyword recognition**
- Custom **DSP pipeline** for audio preprocessing
- **INT8 quantization** and **structured pruning**
- Real-time inference on **Basys 3**
- Blends **deep learning + digital design + embedded architecture**

---

## 💻 8-Bit Simple Computer

<div align="center">

![Processor](https://img.shields.io/badge/Architecture-8--Bit_Computer-850018?style=for-the-badge)
![Datapath](https://img.shields.io/badge/Design-Datapath-171717?style=for-the-badge)
![Control Unit](https://img.shields.io/badge/Logic-Microprogrammed_Control-850018?style=for-the-badge)
![Verilog](https://img.shields.io/badge/HDL-Verilog-171717?style=for-the-badge)

</div>

### Mission
Designed a **microprogrammed 8-bit computer** in Verilog by building both the **datapath** and **control unit**, then implementing a fetch-decode-execute flow in simulation.

### Architecture Graphic
```text
                ┌──────────────┐
                │ Program      │
                │ Counter      │
                └──────┬───────┘
                       │
                       v
                ┌──────────────┐
                │ Instruction  │
                │ Register     │
                └──────┬───────┘
                       │
        ┌──────────────┴──────────────┐
        v                             v
┌──────────────┐              ┌──────────────┐
│ Mapping ROM  │              │ Datapath     │
│ / Sequencing │ ------------>│ ALU / Regs   │
└──────┬───────┘ control       │ Bus / Memory │
       │                       └──────────────┘
       v
┌──────────────┐
│ CAR +        │
│ Control Mem  │
└──────────────┘
```

### Why it’s cool
- Basically a **small CPU**
- Built the internal structure behind instruction execution
- Makes your interest in **computer architecture** super visible
- Shows strong **control logic** and **RTL design** skills

---

## 🔐 Embedded Puzzle Box

<div align="center">

![ESP32](https://img.shields.io/badge/MCU-ESP32-850018?style=for-the-badge&logo=espressif)
![FreeRTOS](https://img.shields.io/badge/RTOS-FreeRTOS-171717?style=for-the-badge)
![WiFi](https://img.shields.io/badge/Connectivity-Wi--Fi-850018?style=for-the-badge)
![Sensors](https://img.shields.io/badge/Inputs-RFID_%2F_Joystick_%2F_LDR-171717?style=for-the-badge)
![OLED](https://img.shields.io/badge/UI-OLED_Display-850018?style=for-the-badge)

</div>

### Mission
Created a multi-stage **interactive puzzle box** using an ESP32, combining sensors, wireless communication, OLED feedback, and puzzle logic into one embedded system.

### System Graphic
```text
     ┌───────────┐
     │   RFID    │
     └─────┬─────┘
           │
     ┌─────v─────┐
     │ Simon     │
     │ Says Game │
     └─────┬─────┘
           │
     ┌─────v─────┐
     │ Lockpick  │
     │ Joystick  │
     └─────┬─────┘
           │
     ┌─────v─────┐
     │ Light     │
     │ Sensor    │
     └─────┬─────┘
           │
     ┌─────v─────────────┐
     │ Wi-Fi Webpage +   │
     │ RSA Final Unlock  │
     └───────────────────┘
```

### Why it’s cool
- Multi-stage embedded system with **game logic**
- Uses **interrupts, ADC, PWM, sensors, OLED, and Wi-Fi**
- Includes a **web-based RSA unlock mechanism**
- Feels like a real engineered product, not just a lab

---

## ⚡ GPU Reliability Research

<div align="center">

![GPU](https://img.shields.io/badge/Platform-Jetson_Nano-850018?style=for-the-badge)
![CUDA](https://img.shields.io/badge/Compute-CUDA-171717?style=for-the-badge)
![NVBitFI](https://img.shields.io/badge/Tool-NVBitFI-850018?style=for-the-badge)
![Fault Injection](https://img.shields.io/badge/Method-Fault_Injection-171717?style=for-the-badge)

</div>

### Mission
Exploring **GPU reliability** by injecting faults into NVIDIA hardware and observing how computation breaks under error conditions.

### Research Graphic
```text
 ┌──────────────┐     ┌──────────────┐     ┌─────────────────────┐     ┌────────────────────┐
 │ CUDA Kernel  │ --> │ Fault Inject │ --> │ Corrupted Execution │ --> │ Outcome Analysis   │
 │ Benchmark    │     │  NVBitFI     │     │ Bit Flips / Errors  │     │ Crash / SDC / etc. │
 └──────────────┘     └──────────────┘     └─────────────────────┘     └────────────────────┘
```

### Keep it cool, not too deep
- Injecting faults into **NVIDIA GPUs**
- Studying how hardware errors affect computation
- Looking at how systems fail under corrupted execution
- A mix of **CUDA**, **hardware behavior**, and **reliability analysis**

---

## 03 // TECH STACK

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d0d0d,100:8b001c&height=70&section=header&text=Technical%20Arsenal&fontSize=28&fontColor=ffffff"/>

<br><br>

### Languages
<img src="https://skillicons.dev/icons?i=c,cpp,py,matlab&theme=dark"/>

### Hardware / Design
![Verilog](https://img.shields.io/badge/Verilog-850018?style=for-the-badge)
![VHDL](https://img.shields.io/badge/VHDL-171717?style=for-the-badge)
![RTL Design](https://img.shields.io/badge/RTL_Design-850018?style=for-the-badge)
![Vivado](https://img.shields.io/badge/Xilinx_Vivado-171717?style=for-the-badge)
![CUDA](https://img.shields.io/badge/CUDA-850018?style=for-the-badge)
![Cadence](https://img.shields.io/badge/Cadence_Virtuoso-171717?style=for-the-badge)

### Embedded / Tools
![ESP32](https://img.shields.io/badge/ESP32-850018?style=for-the-badge&logo=espressif)
![MSP432](https://img.shields.io/badge/MSP432-171717?style=for-the-badge)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-850018?style=for-the-badge)
<img src="https://skillicons.dev/icons?i=linux,git,github,ros,vscode&theme=dark"/>

</div>

---

## 04 // OTHER PROJECTS

| Project | Area | Stack |
|:--|:--|:--|
| HAWK Traffic Light Controller | FPGA FSM Design | Verilog, Basys 3 |
| Artificial Pancreas Prototype | Embedded Sensing | MSP432, ADC, PWM |
| Claw Controller | Real-Time Control | MSP432, PWM |
| Autonomous Rover & Drone | Robotics | ROS 2, ArduPilot |

---

## 05 // BEYOND THE CODE

- IEEE Internal Affairs Officer  
- Robotics & Automation Society — Electrical / Software Team  
- SHPE Member  
- Dean’s List  

---

<div align="center">

## Software is temporary. Silicon is eternal.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,35:30000a,65:850018,100:ff003c&height=120&section=footer"/>

</div>
