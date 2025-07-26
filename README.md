⚡ Intelligent Reactive Energy Management using MATLAB Simulink
📘 Abstract  
This project addresses the issue of poor power factor in industrial electrical systems by developing an intelligent reactive power compensation system. Using MATLAB Simulink, the system simulates load variations, calculates the power factor in real-time, and activates capacitor banks accordingly. This enhances energy efficiency, reduces transmission losses, and avoids utility penalties.
---
🎯 Objective  
- Simulate reactive energy management using MATLAB Simulink.  
- Analyze power factor under dynamic industrial load conditions.  
- Automatically control capacitor banks using logic-based switching.  
- Improve power factor, energy efficiency, and system reliability.
---
⚙️ Tools & Technologies  
- **Simulation Software:** MATLAB Simulink (R2021a)  
- **Libraries Used:** Simscape Electrical, Simulink Logic Blocks  
- **Application Domain:** Industrial Power Systems, Electrical Load Management
---
🧠 Functional Overview  
- **Voltage & Current Monitoring**: Simulates varying industrial load behavior.  
- **Power Factor Calculation**: Calculates real (kW), reactive (kVAR), and apparent power (kVA).  
- **Control Logic**: If the power factor falls below a threshold (e.g., 0.9), capacitor banks are activated.  
- **Capacitor Bank Switching**: Increases the power factor to the optimal range.  
- **Real-Time Feedback**: Continuously monitors the system and adapts capacitor usage.
---
📈 Flow Diagram  
```mermaid
graph TD
    A[Start Simulation] --> B[Monitor Voltage & Current]
    B --> C[Calculate Power Factor]
    C --> D{Is PF < 0.9?}
    D -- Yes --> E[Activate Capacitor Bank]
    D -- No --> F[Maintain Current State]
    E --> G[Update PF]
    F --> G
    G --> H{Continue Simulation?}
    H -- Yes --> B
    H -- No --> I[Stop Simulation]
---
📝 Citation (IEEE Format)
S. Mydeen R, “Intelligent Reactive Energy Management using MATLAB Simulink,” 2024 IEEE International Conference on Smart Technologies and Systems for Next Generation Computing (ICSTSN), Chennai, India, 2024. doi: 10.1109/ICSTSN.2024.10447438
