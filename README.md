# ChipTop – Complete Physical Design Flow

## About
**ChipTop** demonstrates a **complete Physical Design (PD) flow** of a digital chip, implemented from **floorplanning to routing** using industry-standard EDA tools.  
The design integrates **4 macros** and approximately **6,157 standard cells**, driven by a **single 250 MHz clock (4 ns period)**.  

With a **core utilization of 0.70**, the design achieves an optimal balance between performance, area, and routability.  
The PD flow — including **floorplanning, power planning, placement, CTS, routing, and signoff** — was completed successfully with **zero LVS and DRC violations**, resulting in a fully verified and manufacturable layout.

---

## ⚙️ Design Specifications
| Parameter | Description |
|------------|--------------|
| **Clock Period** | 4 ns (250 MHz) |
| **Core Utilization** | 0.70 |
| **Total Standard Cells** | 6157 |
| **Total Macros** | 4 |
| **Clock Ports** | 1 |
| **Violations** | 0 LVS / 0 DRC |
| **Flow Completion** | Successful |

---

## Design Flow Overview
1. **Floorplanning** – Defined core, placed macros, and allocated IOs.  
2. **Power Planning** – Created power rings and straps ensuring even IR drop distribution.  
3. **Placement** – Standard cells placed efficiently with congestion optimization.  
4. **CTS (Clock Tree Synthesis)** – Balanced clock distribution with minimal skew and jitter.  
5. **Routing** – Detailed routing performed with preferred metal directions and congestion control.  
6. **Signoff Checks** – Verified through **LVS** and **DRC** with zero violations.

---

## Results
- Design completed successfully with **no timing or physical violations**.  
- Optimized routing and area efficiency with **0.70 utilization**.  
- Achieved clean **LVS/DRC reports**, confirming design correctness.  

---

## Key Learnings
- Practical understanding of **Physical Design flow** using EDA tools.  
- Hands-on experience in **timing closure, power planning, and routing optimization**.  
- Exposure to **design signoff checks** and the full backend design process.
