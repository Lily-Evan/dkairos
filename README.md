# 🛰️ Particle Detection & Geomagnetic Disturbance Analysis  
### University Assignment – Python Implementation

## 📘 Overview
This repository contains the complete implementation of a two-part university project related to particle detection and geomagnetic disturbance analysis using real satellite data.

## 📂 Project Structure
```
├── data/
│   ├── Indices.mat              # Dst & AL indices (5-min resolution)
│   ├── omni_storms.txt          # OMNI solar-wind data (no header)
│
├── διαστημικος καιρος.ipynb     # Main analysis notebook
│
└── README.md                    # Project documentation

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
🚀 Running the Code

This project is optimized for Google Colab.

To run:

Upload:

Indices.mat

omni_storms.txt

διαστημικος καιρος.ipynb

Open the notebook in Google Colab.

Run all cells.

No local installation required.
```

## 👩‍💻 Author
Παναγιώτα Γροσδούλη
