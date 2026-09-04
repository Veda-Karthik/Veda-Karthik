<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0A0E17,100:141B3C&height=190&section=header&text=VEDA%20KARTHIK&fontSize=44&fontColor=00E5FF&fontAlignY=38&desc=RTL%20%E2%80%A2%20FPGA%20%E2%80%A2%20COMPUTER%20ARCHITECTURE%20%E2%80%A2%206G%20DSP&descAlignY=62&descSize=15&descColor=A78BFA" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=17&duration=3000&pause=1400&color=00E5FF&center=true&vCenter=true&width=620&lines=Electronics+Engineering+%40+IIT+(BHU)+Varanasi;RTL+implementation+%E2%80%94+one+pipeline+stage+at+a+time;Right+now%3A+FPGA+RTL+for+a+6G+ISAC+testbed" alt="Typing SVG" />

<br/>

<img src="https://img.shields.io/badge/STATUS-ACTIVELY_BUILDING-10B981?style=for-the-badge&labelColor=0A0E17" />
<img src="https://img.shields.io/badge/BASE-IIT_(BHU)_VARANASI-3B82F6?style=for-the-badge&labelColor=0A0E17" />
<img src="https://img.shields.io/badge/DOMAIN-HARDWARE_%2F_DSP-8B5CF6?style=for-the-badge&labelColor=0A0E17" />

</div>

<p align="center">◆⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯◆</p>

### Welcome to the lab.

I'm an Electronics Engineering student at **IIT (BHU) Varanasi**, working from the gate level up — digital logic, into RTL, into FPGA, into full architectures. I care about *what's actually running on the silicon*, not just the algorithm on paper. Currently splitting my time between a from-scratch RISC-V pipeline and RTL work on a 6G joint-sensing-and-communication testbed.

<p align="center">◆⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯◆</p>

## 🧬 The Build Pipeline

<p align="center">
<img src="https://img.shields.io/badge/DIGITAL_LOGIC-00E5FF?style=flat-square&labelColor=0A0E17"/> ➜
<img src="https://img.shields.io/badge/VERILOG-00E5FF?style=flat-square&labelColor=0A0E17"/> ➜
<img src="https://img.shields.io/badge/RTL_DESIGN-3B82F6?style=flat-square&labelColor=0A0E17"/> ➜
<img src="https://img.shields.io/badge/FPGA-3B82F6?style=flat-square&labelColor=0A0E17"/> ➜
<img src="https://img.shields.io/badge/COMPUTER_ARCHITECTURE-3B82F6?style=flat-square&labelColor=0A0E17"/> ➜
<img src="https://img.shields.io/badge/RISC--V-8B5CF6?style=flat-square&labelColor=0A0E17"/> ➜
<img src="https://img.shields.io/badge/DSP_%2F_OFDM-8B5CF6?style=flat-square&labelColor=0A0E17"/> ➜
<img src="https://img.shields.io/badge/ADVANCED_HARDWARE-D946EF?style=flat-square&labelColor=0A0E17"/>
</p>

<p align="center">◆⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯◆</p>

## ⚙ Active Builds

```
┌────────────────────────────────────────────────────────────┐
│  ACTIVE BUILDS                                               │
├────────────────────────────────────────────────────────────┤
│  ⚡  Pipelined RISC-V Processor                [Verilog]      │
│  📡  6G ISAC — OFDM RTL, subcarrier mapping     [FPGA]        │
│  🧠  Computer Architecture self-study (RISC-V, Patterson &   │
│      Hennessy)                                                │
└────────────────────────────────────────────────────────────┘
```

<p align="center">◆⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯◆</p>

## 🔩 Projects

### ⚡ Pipelined RISC-V Processor
<img src="https://img.shields.io/badge/STATUS-IN_PROGRESS-F59E0B?style=flat-square&labelColor=0A0E17" />

Building a RISC-V core up from a single-cycle datapath toward a full 5-stage pipeline, in Verilog.

**Architecture**
- RV32I datapath and control unit, built stage by stage
- Register file and instruction/data memory modeled in RTL
- Working through pipeline hazards — forwarding, stalling, branch resolution

`Verilog` `RISC-V` `RTL` `Computer Architecture`

**Repository:** `[PROJECT_REPOSITORY_LINK]`

---

### 📡 FPGA OFDM / IFFT Hardware
<img src="https://img.shields.io/badge/STATUS-IN_PROGRESS-F59E0B?style=flat-square&labelColor=0A0E17" />

RTL for the OFDM signal chain — the hardware side of turning symbols into a transmittable waveform.

**Architecture**
- IFFT-based OFDM symbol generation (bit reversal, butterfly stages)
- Subcarrier mapping and BPSK constellation handling
- Fixed-point arithmetic in Q1.15 for FPGA-friendly datapaths

`Verilog` `FPGA` `OFDM` `Fixed-Point`

**Repository:** `[PROJECT_REPOSITORY_LINK]`

---

### 🛰 6G Joint Sensing & Communication Testbed
<img src="https://img.shields.io/badge/STATUS-ACTIVE_RESEARCH-10B981?style=flat-square&labelColor=0A0E17" />

*"Advancing 6G: Development of Test-Beds for Joint Sensing and Communication Systems."*

My role is RTL implementation — taking algorithms from the project team and turning them into working Verilog on FPGA.

**Architecture**
- FPGA-based RTL for an OFDM baseband transmitter
- Current stage: subcarrier mapping, Q1.15 fixed-point, verified in Icarus Verilog
- Sits at the intersection of communication systems and sensing hardware

`Verilog` `FPGA` `OFDM` `6G` `RTL`

**Repository:** `[PROJECT_REPOSITORY_LINK]`

<p align="center">◆⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯◆</p>

## 🧠 Tech Stack

**Hardware**
<br/>
<img src="https://img.shields.io/badge/Verilog-00E5FF?style=flat-square&labelColor=0A0E17"/>
<img src="https://img.shields.io/badge/RTL_Design-00E5FF?style=flat-square&labelColor=0A0E17"/>
<img src="https://img.shields.io/badge/FPGA-00E5FF?style=flat-square&labelColor=0A0E17"/>
<img src="https://img.shields.io/badge/Digital_Logic_Design-00E5FF?style=flat-square&labelColor=0A0E17"/>

**Architecture**
<br/>
<img src="https://img.shields.io/badge/RISC--V-3B82F6?style=flat-square&labelColor=0A0E17"/>
<img src="https://img.shields.io/badge/CPU_Design-3B82F6?style=flat-square&labelColor=0A0E17"/>
<img src="https://img.shields.io/badge/Pipelining-3B82F6?style=flat-square&labelColor=0A0E17"/>

**DSP / Communication**
<br/>
<img src="https://img.shields.io/badge/OFDM-8B5CF6?style=flat-square&labelColor=0A0E17"/>
<img src="https://img.shields.io/badge/IFFT-8B5CF6?style=flat-square&labelColor=0A0E17"/>
<img src="https://img.shields.io/badge/BPSK-8B5CF6?style=flat-square&labelColor=0A0E17"/>
<img src="https://img.shields.io/badge/QAM-8B5CF6?style=flat-square&labelColor=0A0E17"/>
<img src="https://img.shields.io/badge/Fixed--Point_Arithmetic-8B5CF6?style=flat-square&labelColor=0A0E17"/>

**Programming**
<br/>
<img src="https://img.shields.io/badge/C-64748B?style=flat-square&labelColor=0A0E17"/>
<img src="https://img.shields.io/badge/MATLAB-64748B?style=flat-square&labelColor=0A0E17"/>

<p align="center">◆⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯◆</p>

## 📊 Snapshot

<p align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=[GITHUB_USERNAME]&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0A0E17&title_color=00E5FF&icon_color=8B5CF6&text_color=E6F1FF"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=[GITHUB_USERNAME]&layout=compact&theme=tokyonight&hide_border=true&bg_color=0A0E17&title_color=00E5FF&text_color=E6F1FF"/>
</p>

<p align="center">◆⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯⎯◆</p>

<p align="center"><i>"Life is about constant exploring and improving."</i></p>

<p align="center">
<a href="[LINKEDIN]">LinkedIn</a> ·
<a href="mailto:[EMAIL]">Email</a> ·
<a href="[PORTFOLIO_OR_OTHER_LINK]">Portfolio</a>
</p>
