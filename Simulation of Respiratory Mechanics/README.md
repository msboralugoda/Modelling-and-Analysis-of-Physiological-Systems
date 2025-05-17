# Simulation of Respiratory Mechanics

This project presents a simulation-based analysis of respiratory mechanics under different pulmonary conditions using a MATLAB-Simulink GUI model. The simulations include normal lung function, a restrictive condition (e.g., pulmonary fibrosis), and an obstructive condition (e.g., COPD).

## 🧠 What I Learned

Through this simulation, I gained valuable insights into:

- **Lung Compliance and Airway Resistance**: How changes in these parameters influence respiratory performance and minute ventilation.
- **Restrictive vs Obstructive Pathophysiology**: The distinct mechanical impacts of diseases like pulmonary fibrosis and COPD on lung behavior.
- **Interpreting Ventilator Waveforms**: Understanding real-time plots of transpulmonary pressure, alveolar flow, and lung volume to assess respiratory efficiency.
- **Minute Ventilation vs Alveolar Ventilation**: Why total airflow alone isn't enough to evaluate effective gas exchange, especially in obstructive conditions.
- **Parameter Tuning for Intervention**: How modifying ventilator settings can potentially mitigate disease effects by improving lung performance.

## 🧪 Simulation Setup

**Tool Used**:  
Simulink GUI – *Simulation of Respiratory Mechanics* by Rodriguez & Guerrero  
[MATLAB File Exchange Link](https://www.mathworks.com/matlabcentral/fileexchange/75335)

**Fixed Ventilator Parameters**:
- Breaths Per Minute (BPM): 15  
- Peak Pressure: 10 cmH₂O  
- I:E Ratio: 1:1  
- PEEP: 0 cmH₂O  

**Adjusted Physiological Variables**:
- Lung Compliance  
- Thoracic Compliance  
- Central & Peripheral Airway Resistance  
- Tissue Compliance

## 📊 Simulation Scenarios

### ✅ Normal Lung Function
- **Lung Compliance**: 0.1 L/cmH₂O  
- **Minute Ventilation**: 7.5 L/min  
- **Outcome**: Efficient ventilation and healthy flow dynamics.



### ⚠️ Restrictive Lung Condition (e.g., Pulmonary Fibrosis)
- **Lung Compliance**: 0.03 L/cmH₂O  
- **Minute Ventilation**: 3 L/min  
- **Outcome**: Severely reduced tidal volume; inefficient gas exchange.



### ❗ Obstructive Lung Condition (e.g., COPD)
- **Peripheral Resistance**: 5 cmH₂O·s/L  
- **Minute Ventilation**: 7.74 L/min  
- **Outcome**: Air trapping and dynamic hyperinflation despite near-normal minute ventilation.



## 📈 Minute Ventilation Comparison

| Condition    | Minute Ventilation | Effective Gas Exchange |
|--------------|--------------------|-------------------------|
| Normal       | 7.5 L/min          | Efficient               |
| Restrictive  | 3.0 L/min          | Poor                    |
| Obstructive  | 7.74 L/min         | Compromised             |


