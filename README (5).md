# 🛰️ Particle Detection & Geomagnetic Disturbance Analysis  
### University Assignment – Python Implementation

## 📘 Overview
This repository contains the complete implementation of a two-part university project related to particle detection and geomagnetic disturbance analysis using real satellite data.

## 📂 Project Structure
```
├── data/
│   ├── Indices.mat
│   ├── omni_storms.txt
├── src/
│   ├── exercise1_particles.py
│   ├── exercise2_geomagnetic.py
├── results/
│   ├── plots/
│   ├── tables/
└── README.md
```

## 🧪 Exercise 1 – Particle Detection
- Mean energy calculation per channel  
- Energy width estimation  
- Differential flux computation  
- Physics: Charged-particle motion in a magnetic field

## 🌍 Exercise 2 – Geomagnetic Disturbances
- Time-series analysis of Dst & AL indices  
- Automatic storm detection (Dst < −50 nT)  
- Storm phase identification (main & recovery)  
- OMNI solar-wind data analysis  
- Variables: V, Pdyn, Bz GSM  

## 📊 Key Scientific Results
- Strong storm detected: **Dst ≈ −106 nT** (17 March 2013)  
- Recovery phase duration: **~3.3 days**  
- Solar-wind drivers: elevated speed, dynamic pressure, strong southward IMF Bz  

## 🛠️ Technologies
Python, NumPy, SciPy, Pandas, Matplotlib

## 🚀 Running the Code
```
python3 src/exercise1_particles.py
python3 src/exercise2_geomagnetic.py
```

## 👩‍💻 Author
Παναγιώτα Γροσδούλη
