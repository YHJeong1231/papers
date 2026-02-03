# 📄 Research Papers – PMSM Estimation and Validation-Oriented Studies

This repository contains three peer-reviewed research papers from my master’s program, focusing on **Permanent Magnet Synchronous Motor (PMSM) systems** and **observer-based estimation methods** validated through extensive simulations and experimental-level modeling environments.

My research emphasizes not only theoretical design using **LMI-based observers and neural networks**, but also **practical verification in PMSM drive systems**, including nonlinear inverter effects, disturbance rejection, and rapidly varying load torques typically observed in compressor applications.

All proposed algorithms were systematically validated through:

- High-fidelity PMSM and inverter models  
- Discrete-time simulation frameworks  
- Comparison of estimation accuracy using RMSE metrics  
- Robustness analysis under measurement noise and nonlinear disturbances  
- $H_\infty$-based performance evaluation  

---

## 📑 Included Papers

### 🔹 IECON 2025  
**LMI-Based Neural Observer for PMSM for State and Nonlinearity Estimation**

- Compressor-type periodic load torque modeling  
- Unified gain design in descrete-time domain for implementation simplicity with LMI-based optimization
- Reduce effects such as measurement noise and disturbances $H_\infty$-based optimization 
- Thorough validation through time-domain simulations  
- **PDF**: [Download](IECON2025.pdf)

---

### 🔹 ISIE 2024 & ICROS 2024
**Neural Network-based Nonlinearity Estimation of Voltage Source Inverter for Synchronous Machine Drives**

- Neural Network-based observer design with Lypunov function stability
- Comparative RMSE-based evaluation  
- Validation using PMSM simulation environments
- **PDF(ISIE2024)**: [Download](ISIE2024.pdf)
- **PDF(ICROS2024)**: [Download](ICROS2024.pdf)

---

## 🎯 Research Focus

- PMSM Modeling and Drive Systems  
- Load Torque Estimation for Compressor Applications  
- Inverter Nonlinearity Compensation  
- Neural Network-based Observers  
- LMI-based & Lyapunov Stability Analysis  
- Validation-Driven Control Design  

---

## 🔍 Why This Matters for Industry

These works were conducted with the goal of **bridging theoretical observer design and industrial PMSM applications**, ensuring that every proposed algorithm is:

- Implementable in discrete-time controllers & observers
- Robust to sensor noise and nonlinear effects  
- Suitable for compressor-driven PMSM systems  
- Verified through realistic simulation environments  

---

> **Validation-focused PMSM estimation research portfolio featuring LMI-based neural observers verified through high-fidelity compressor-drive simulations and RMSE-based performance evaluation.**
