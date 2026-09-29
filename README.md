# 🔋 Smart Renewable Microgrid Controller

A control systems project simulating dynamic power management for a changing renewable energy grid.

## 💡 The Motivation
Control loops are the hidden heart of mechatronics. Whether it's a robotic arm balancing its load or a system managing grid energy, software must adapt instantly to change. I built this simulation to practice programmatic problem-solving, exploring how modern green energy systems automatically balance unpredictable power sources against consumer demands.

## 🛠️ How the System Works
1. **The Infrastructure Layer (Wokwi):** An Arduino node simulates varying green energy inputs (like shifting solar and wind power levels) through analog inputs, while a digital toggle switch simulates main utility grid faults or power cuts.
2. **The Automation Logic (Google Colab):** A Python script calculates the overall energy balance in real-time. If green power drops or the main grid fails, the script automatically triggers stepped load-shedding commands to keep critical systems online.

## 🔗 Live Interactive Links
* **Wokwi Microgrid Circuit Simulator:** [Launch the Wokwi Simulation](https://wokwi.com/projects/475944125439683585)
* **Google Colab Control Logic Engine:** [Open the Google Colab Notebook](https://colab.research.google.com/drive/1kcMNQHS0DypNDUv9YUw6tdWSyF7OoObQ?usp=sharing)

## 🧠 What I Learned & Practised
* **Algorithmic Thinking**: Programmed automation logic that makes real-time decisions, such as cutting secondary factory loads when simulated solar input drops too low.
* **Control Loops & Balancing**: Gained an understanding of microgrid isolation, battery storage thresholds, and the challenges of maintaining system stability.
* **Software-Driven Hardware**: Practised translating live hardware sensor feeds into active software rules that alter the state of an entire system.
* **Problem Analysis**: Improved my ability to sketch out system logic and state-management rules before writing functional software code.

---

### 🚀 Future Steps
I want to translate this conceptual Python control logic into industrial PLC Ladder Logic to see how a physical industrial controller would execute the exact same grid balancing task.
