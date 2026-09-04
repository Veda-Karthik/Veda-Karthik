<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1026,50:2B1055,100:5B21B6&height=190&section=header&text=VEDA%20KARTHIK&fontSize=44&fontColor=22D3EE&fontAlignY=35&desc=I%20build%20hardware%20for%20signals&descAlignY=55&descSize=17&descColor=F0ABFC" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=17&duration=3000&pause=1400&color=22D3EE&center=true&vCenter=true&width=640&lines=Electronics+Engineering+%40+IIT+(BHU)+Varanasi;RTL+for+OFDM%2C+IFFT%2C+and+6G+ISAC+hardware;From+baseband+math+to+bits+on+an+FPGA" alt="Typing SVG" />

<br/>

<img src="https://img.shields.io/badge/STATUS-ON_AIR-34D399?style=for-the-badge&labelColor=0B1026" />
<img src="https://img.shields.io/badge/BASE-IIT_(BHU)_VARANASI-3B82F6?style=for-the-badge&labelColor=0B1026" />
<img src="https://img.shields.io/badge/DOMAIN-DSP_%2F_6G_HARDWARE-A855F7?style=for-the-badge&labelColor=0B1026" />

</div>

<p align="center">∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿</p>

### Everything here is a signal, somewhere.

I'm an Electronics Engineering student at **IIT (BHU) Varanasi**, working on the hardware that turns waveforms into bits and back — RTL implementation for a 6G joint-sensing-and-communication testbed, alongside a RISC-V processor built from the ground up. I like the layer where math (FFTs, fixed-point, constellations) becomes a physical circuit.

<p align="center">∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿</p>

## 📡 Signal Chain

<p align="center">
<img src="https://img.shields.io/badge/DIGITAL_LOGIC-22D3EE?style=flat-square&labelColor=0B1026"/> ➜
<img src="https://img.shields.io/badge/VERILOG-22D3EE?style=flat-square&labelColor=0B1026"/> ➜
<img src="https://img.shields.io/badge/RTL_DESIGN-3B82F6?style=flat-square&labelColor=0B1026"/> ➜
<img src="https://img.shields.io/badge/FPGA-3B82F6?style=flat-square&labelColor=0B1026"/> ➜
<img src="https://img.shields.io/badge/COMPUTER_ARCHITECTURE-3B82F6?style=flat-square&labelColor=0B1026"/> ➜
<img src="https://img.shields.io/badge/RISC--V-A855F7?style=flat-square&labelColor=0B1026"/> ➜
<img src="https://img.shields.io/badge/DSP_%2F_OFDM-A855F7?style=flat-square&labelColor=0B1026"/> ➜
<img src="https://img.shields.io/badge/ADVANCED_HARDWARE-EC4899?style=flat-square&labelColor=0B1026"/>
</p>

<p align="center">∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿</p>

## 🎛 On Air

```
┌────────────────────────────────────────────────────────────┐
│  TRANSMITTING                                                │
├────────────────────────────────────────────────────────────┤
│  📡  6G ISAC Testbed — RTL implementation        [ACTIVE]     │
│  🌀  OFDM / IFFT hardware blocks                  [ACTIVE]    │
│  ⚙   Pipelined RISC-V Processor                  [BUILDING]  │
└────────────────────────────────────────────────────────────┘
```

<p align="center">∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿</p>

## 🔬 Projects

### 🛰 6G Joint Sensing & Communication Testbed
<img src="https://img.shields.io/badge/STATUS-ACTIVE_RESEARCH-34D399?style=flat-square&labelColor=0B1026" />

*"Advancing 6G: Development of Test-Beds for Joint Sensing and Communication Systems."*

My role is RTL implementation — taking algorithms from the project team and turning them into working Verilog on FPGA.

**Architecture**
- FPGA-based RTL for an OFDM baseband transmitter
- Current stage: subcarrier mapping, Q1.15 fixed-point, verified in Icarus Verilog
- Sits at the intersection of communication systems and sensing hardware

`Verilog` `FPGA` `OFDM` `6G` `RTL`

**Repository:** `[PROJECT_REPOSITORY_LINK]`

---

### 🌀 FPGA OFDM / IFFT Hardware
<img src="https://img.shields.io/badge/STATUS-IN_PROGRESS-F59E0B?style=flat-square&labelColor=0B1026" />

RTL for the OFDM signal chain — the hardware side of turning symbols into a transmittable waveform.

**Architecture**
- IFFT-based OFDM symbol generation (bit reversal, butterfly stages)
- Subcarrier mapping and BPSK constellation handling
- Fixed-point arithmetic in Q1.15 for FPGA-friendly datapaths

`Verilog` `FPGA` `OFDM` `Fixed-Point`

**Repository:** `[PROJECT_REPOSITORY_LINK]`

---

### ⚡ Pipelined RISC-V Processor
<img src="https://img.shields.io/badge/STATUS-IN_PROGRESS-F59E0B?style=flat-square&labelColor=0B1026" />

Building a RISC-V core up from a single-cycle datapath toward a full 5-stage pipeline, in Verilog.

**Architecture**
- RV32I datapath and control unit, built stage by stage
- Register file and instruction/data memory modeled in RTL
- Working through pipeline hazards — forwarding, stalling, branch resolution

`Verilog` `RISC-V` `RTL` `Computer Architecture`

**Repository:** `[PROJECT_REPOSITORY_LINK]`

<p align="center">∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿</p>

## 🧠 Tech Stack

**DSP / Communication**
<br/>
<img src="https://img.shields.io/badge/OFDM-A855F7?style=flat-square&labelColor=0B1026"/>
<img src="https://img.shields.io/badge/IFFT-A855F7?style=flat-square&labelColor=0B1026"/>
<img src="https://img.shields.io/badge/BPSK-A855F7?style=flat-square&labelColor=0B1026"/>
<img src="https://img.shields.io/badge/QAM-A855F7?style=flat-square&labelColor=0B1026"/>
<img src="https://img.shields.io/badge/Fixed--Point_Arithmetic-A855F7?style=flat-square&labelColor=0B1026"/>

**Hardware**
<br/>
<img src="https://img.shields.io/badge/Verilog-22D3EE?style=flat-square&labelColor=0B1026"/>
<img src="https://img.shields.io/badge/RTL_Design-22D3EE?style=flat-square&labelColor=0B1026"/>
<img src="https://img.shields.io/badge/FPGA-22D3EE?style=flat-square&labelColor=0B1026"/>
<img src="https://img.shields.io/badge/Digital_Logic_Design-22D3EE?style=flat-square&labelColor=0B1026"/>

**Architecture**
<br/>
<img src="https://img.shields.io/badge/RISC--V-3B82F6?style=flat-square&labelColor=0B1026"/>
<img src="https://img.shields.io/badge/CPU_Design-3B82F6?style=flat-square&labelColor=0B1026"/>
<img src="https://img.shields.io/badge/Pipelining-3B82F6?style=flat-square&labelColor=0B1026"/>

**Programming**
<br/>
<img src="https://img.shields.io/badge/C-64748B?style=flat-square&labelColor=0B1026"/>
<img src="https://img.shields.io/badge/MATLAB-64748B?style=flat-square&labelColor=0B1026"/>

<p align="center">∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿</p>

## 📈 Waveform (Activity)

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=[GITHUB_USERNAME]&theme=react-dark&hide_border=true&bg_color=0B1026&color=22D3EE&line=A855F7&point=EC4899&area=true" width="100%"/>
</p>

<p align="center">∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿∿</p>

<p align="center"><i>"Life is about constant exploring and improving."</i></p>

<p align="center">
<a href="[LINKEDIN]">LinkedIn</a> ·
<a href="mailto:[EMAIL]">Email</a> ·
<a href="[PORTFOLIO_OR_OTHER_LINK]">Portfolio</a>
</p>
