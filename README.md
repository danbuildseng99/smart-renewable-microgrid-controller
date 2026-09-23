# Industry 4.0 Smart Renewable Microgrid Controller (Capstone Tier)

## System Overview
This project models a localized industrial power distribution microgrid. It showcases the integration of embedded controls with grid infrastructure management software, automatically routing power generation inputs and managing load configurations during critical utility grid faults.

## Engineering Architecture
1. **The Infrastructure Layer (Arduino/C++):** Simulates dynamic renewable energy production variables (Solar arrays via A0, Wind turbines via A1) and maps discrete utility substation connectivity status via an interrupt-style digital toggle loop.
2. **The Automation Controller Logic (Python):** Operates as a Supervisory Control layer. It calculates generation balances, maps energy production metrics against structural network loading, and executes stepped load-shedding commands when local sub-grids isolate.

## Key Technical Proficiencies Demonstrated
* **Control Systems Engineering:** Implementing multi-input mathematical optimization scripts to manage distribution resources.
* **Renewable Energy Infrastructure Concept:** Practical grasp of microgrid isolation, battery balancing thresholds, and grid-tied operations.
* **Software-Driven Hardware Integration:** Translating hardware array telemetry data feeds into actionable automation instructions.

## Technical Project Artifacts
* **Wokwi Microgrid Circuit Simulator:** [https://wokwi.com/projects/475944125439683585]
* **Google Colab Control Logic Engine:** [https://colab.research.google.com/drive/1szUUU7FOn6-40OLsSRysVgBG48l0Ymu3?usp=sharing]
