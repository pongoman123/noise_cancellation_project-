# Active Noise Cancellation (ANC) Analog Circuit Design

A dual-op-amp active noise cancellation circuit designed in LTspice, utilizing machine learning optimization to automatically determine ideal resistor ($R$) and capacitor ($C$) values for targeted noise attenuation.

## 📌 Overview
This project focuses on analog signal processing and active noise suppression. By combining LTspice simulations with an AI-driven optimization pipeline, the system iteratively computes and tunes the optimal $R$ and $C$ component values required to achieve precise signal phase-inversion and maximum acoustic attenuation across operational bandwidths.

## 🛠️ Tech Tools & Instruments
* **Simulation Software:** LTspice
* **Optimization & Scripting:** Python (Machine Learning / Automated Parameter Tuning)
* **Key Concepts:** Analog Electronics, Signal Processing, Frequency Sweeps, Phase-Inversion Topologies

## ⚙️ Key Workflow & Implementation
1. **Circuit Topology:** Designed a dual-op-amp active noise cancellation circuit in LTspice incorporating phase-inversion and transmission line propagation delays.
2. **AI-Driven Parameter Optimization:** Implemented a machine learning optimization approach to automatically search and find the ideal $R$ and $C$ network values for target frequency response curves.
3. **Validation & Testing:** Executed AC frequency sweeps (10 Hz to 100 kHz) and processed real WAV audio files directly within SPICE simulation engines to measure acoustic attenuation using the AI-tuned parameters.

## 🚀 How to Run
1. Run the optimization script in Python to compute the target $R$ and $C$ parameter values.
2. Download and open LTspice, then load the `.asc` schematic file.
3. Apply the optimized component values and run the simulation to view AC frequency response curves and transient noise cancellation waveforms.
