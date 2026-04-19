# 🧠 ANN Regression — Code Review & Comparison
 
> PyTorch ANN for regression on the **Combined Cycle Power Plant** dataset.
> -----
> ## 📐 Model Architecture
 
```
Input (4 features: AT, V, AP, RH)
        ↓
  Linear(4 → 6) + ReLU
        ↓
  Linear(6 → 6) + ReLU
        ↓
   Linear(6 → 1)
        ↓
  Output (PE — Produced Energy)
```
 ## 📁 Dataset
 
**Combined Cycle Power Plant Dataset**  
Features: `AT` (Temperature), `V` (Vacuum), `AP` (Pressure), `RH` (Humidity)  
Target: `PE` (Net hourly electrical energy output in MW)
 
