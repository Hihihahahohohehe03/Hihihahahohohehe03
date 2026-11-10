<div align="center">
  <img src="./hippo.png" width="180" alt="HIPPO LAB Mascot">
</div>

<div align="center">

# 🦛 HIPPO LAB

### Electronics Engineering | Semiconductor | Embedded Systems

*Exploring the intersection of hardware, software, and semiconductor technology.*

</div>

---

## 👋 About Me

Hello! I'm an Electronics Engineering student passionate about
semiconductor devices and embedded systems.

- 🔬 **Semiconductor:** Device Physics, Process Engineering
- ⚡ **Hardware:** RISC-V, FPGA, Computer Architecture
- 💻 **Programming:** C, Python, Verilog
- 🎯 **Goal:** Semiconductor Process & Device Engineering

---


## 🛠️ Tech Stack

### 💻 Programming & HDL
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-555555?style=for-the-badge&logoColor=white)

### ⚙️ EDA & Simulation Tools
![Vivado](https://img.shields.io/badge/AMD_Vivado-ED1C24?style=for-the-badge&logoColor=white)
![Silvaco](https://img.shields.io/badge/Silvaco_ATLAS-236B8E?style=for-the-badge&logoColor=white)
![Verilator](https://img.shields.io/badge/Verilator-34495E?style=for-the-badge&logoColor=white)

### 🖥️ Development Environment
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)


---

## 🚀 Featured Projects

### 🔬 MIM Capacitor Research
- Surface roughness and capacitance analysis
- Semiconductor device simulation

### ⚡ RISC-V Processor Labs
- RISC-V Assembly programming
- AXI interface and pipeline analysis

### 🤖 MNIST CNN
- Image classification using PyTorch
- Convolutional neural network implementation

---


## 🔍 Recent Research : PN Junction Diode Simulation

### 1. Overview

This project focuses on the modeling and simulation of a PN junction diode using **Silvaco ATLAS TCAD**.

The objective is to investigate the device structure, doping configuration, and electrical characteristics of a PN junction under different bias conditions.

### 2. Device Structure

The PN junction diode consists of two silicon regions with different doping types.

- **P-type region:** 1 × 10^16 cm^-3
- **N-type region:** 1 × 10^16 cm^-3
- **Device dimensions:** 2 µm × 1 µm
- **Anode:** Left boundary
- **Cathode:** Right boundary

#### 2D Structure and Mesh

![PN Junction Diode Structure](./PNDiode_IMG1.jpg)

*Figure 1. Two-dimensional silicon PN junction structure and computational mesh generated using Silvaco ATLAS.*

The simulation domain is divided into two regions, with the PN junction located at x = 1 µm.

A numerical mesh is generated to discretize the device structure for semiconductor device simulation.

### 3. Simulation Setup

**Simulation Tool:** Silvaco ATLAS TCAD

**Physical Models:**
- Concentration-dependent mobility (CONMOB)
- Boltzmann carrier statistics

**Numerical Method:**
- Newton method

**Temperature:** 300 K

### 4. Electrical Characterization

The electrical behavior of the PN junction diode is investigated by applying different voltage biases to the anode.

The simulation is configured to obtain current-voltage (I-V) characteristics.

### 5. Simulation Results

Additional results, including I-V characteristics and potential distributions, will be documented here.

### 6. Tools

- Silvaco ATLAS
- DeckBuild
- TonyPlot


---

<div align="center">

**Keep Learning. Keep Building.**

</div>
