# PVT-analysis-of-DG-TFET
PVT analysis of a 30 nm Double-Gate Tunnel Field-Effect Transistor (DG-TFET) using SILVACO ATLAS TCAD and Origin, investigating temperature, voltage scaling, gate misalignment, oxide thickness, work function, leakage current, and device performance.

# PVT Analysis of Double-Gate TFET (DG-TFET)

## 1. Project Overview
This project investigates the Process-Voltage-Temperature (PVT) characteristics of a 30 nm Double-Gate Tunnel Field-Effect Transistor (DG-TFET) using SILVACO ATLAS TCAD for device simulation and Origin software for data analysis and visualization.

The study evaluates how device geometry, gate-stack parameters, supply voltage, and temperature influence the electrical performance of a DG-TFET, with an emphasis on low-power operation and leakage behavior.

## 2. Objectives
- Simulate a 30 nm Double-Gate TFET using SILVACO ATLAS TCAD.
- Analyze the effects of gate misalignment and gate-oxide thickness.
- Investigate Si–SiO₂ interface fixed charge and gate-metal work function.
- Study temperature effects over 298 K–448 K.
- Examine supply-voltage scaling from 1.5 V to 0.1 V.
- Evaluate ON-current, OFF-current, threshold voltage, subthreshold swing (SS), and the ION/IOFF ratio.
- Analyze ambipolar current and p-i-n forward leakage.

## 3. Tools and Technology
- Device simulation: SILVACO ATLAS TCAD
- Data analysis and plots: Origin
- Device: 30 nm Double-Gate Tunnel Field-Effect Transistor (DG-TFET)

## 4. Parameters Investigated
| Parameter | Range or study |
|-----------|----------------|
| Bottom-gate misalignment | −15 nm to +15 nm |
| Gate-oxide thickness | 3 nm to 5 nm |
| Gate-metal work function | 3.9 eV to 5.2 eV |
| Temperature | 298 K to 448 K |
| Supply voltage | 1.5 V to 0.1 V |
| Interface fixed charge | Si–SiO₂ interface variation |

## 5. Key Findings Reported in the Dissertation
- Gate misalignment: Optimum performance was observed at 0 nm misalignment, with ION approximately 1.73 × 10⁻⁶ A/µm.
- Gate-oxide thickness: The 3 nm oxide produced the highest ON-current among the evaluated thicknesses, with a measured SS of 50.47 mV/decade.
- Gate-metal work function: A value of 4.2 eV was identified as optimum, with SS approximately 45.87 mV/decade and an improved ION/IOFF trade-off.
- Temperature: Across 298 K–448 K, reported ION values ranged from approximately 1 × 10⁻⁶ to 3.25 × 10⁻⁶ A/µm, while IOFF ranged from approximately 1.36 × 10⁻¹² to 3.19 × 10⁻¹² A/µm.
- Voltage scaling and leakage: Supply-voltage scaling and ambipolar and p-i-n forward leakage behavior were investigated to assess low-power performance and potential limitations.

## 6. Suggested Repository Structure
pvt-analysis-dg-tfet/
├── README.md
├── report/
│   └── dissertation_summary.pdf
├── data/
│   └── README.md
├── plots/
│   └── README.md
└── images/
    └── README.md

## 7. Author
Sarif Ahmad
M.Tech in Electronic Circuits and System Design  
Aligarh Muslim University (AMU)

LinkedIn: https://www.linkedin.com/in/ahmad-a-68b500138/
**Note:** This repository documents my M.Tech dissertation on DG-TFET device simulation and PVT analysis. It is separate from my RTL design and functional verification projects.
