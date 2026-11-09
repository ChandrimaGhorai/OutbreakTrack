# OutbreakTracker 🦠📈

OutbreakTracker is an epidemiological simulation and compartmental modeling platform designed to track disease spread within populations. Utilizing Susceptible-Infectious-Recovered (SIR) differential equations (`odeint`), it models real-time population shifts and evaluates critical transmission dynamics under preset or custom scenarios.

## Key Features
- **Dual-Mode Operation:** Choose between *Live Data Pull-up* (preset disease profiles like COVID variants or typhoid) and *Interactive Mode* (custom population parameters).
- **Differential Equation Modeling:** Employs rigorous mathematical modeling (`scipy.integrate.odeint`) to simulate continuous population drift between Susceptible, Carrier/Infectious, and Recovered states.
- **Transmission & Recovery Tuning:** Adjust transmission rates ($\beta$) and recovery rates ($\gamma$) to instantly observe shifts in the basic reproduction number ($R_0$) and epidemic curves.
- **Automated Diagnostic Reporting:** Computes peak carrier loads, time-to-peak, cumulative case counts, and estimated $R_0$ alongside automatic plot generation.

## Workflow Overview
1. **Mode Selection:** Choose between loading preset pathogen data or entering custom population parameters interactively.
2. **Simulation Execution:** Differential equations model the continuous transition across Susceptible, Infectious, and Recovered compartments over time.
3. **Curve & Metric Analysis:** Evaluates peak timing, severity, and reproduction numbers based on variable transmission rates.
4. **Output & Reporting:** Generates comprehensive epidemiological metrics and automated outbreak progression plots.

## Usage
You can run the complete simulation pipeline interactively via Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1AiAsGa59E86I3kml50yBlgrKFU6D6M-5?usp=sharing)
