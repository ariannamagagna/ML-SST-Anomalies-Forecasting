# ML for SST Anomalies Forecasting

Forecasting Sea Surface Temperature (SST) anomalies using machine learning and empirical orthogonal function (EOF) analysis on ERA5 data.

![image](https://github.com/user-attachments/assets/d32835b0-0ce6-45c2-8c79-c3ce8176ef45)

---

## Overview

This project evaluates the performance of **LSTM** and **MLP** architectures in predicting SST anomalies based on **EOF-decomposed ERA5** time series.

### Objectives
- Model SST variability using historical reanalysis data
- Compare performance of LSTM and MLP architectures
- Investigate temporal dependencies in SST anomaly patterns

---

## Methodology

### Preprocessing
- Seasonal decomposition
- PACF analysis for lag selection
- EOF decomposition of SST fields

### Modeling
- LSTM and MLP architecture design
- Training and validation
- Performance evaluation (RMSE, anomaly correlation)

### Key Findings
- **LSTM** outperforms **MLP**, especially in regions with strong temporal dynamics
- EOF decomposition improves model interpretability and robustness

---

## Tools & Libraries

- `numpy`, `scipy`, `xarray`, `netCDF4`  
- `matplotlib`, `cartopy`, `joblib`  
- `tensorflow`, `keras`

---

## Authors

**Arianna Magagna**  
BSc Physics - University of Trento  
MSc Science of Climate — University of Bologna  
📫 Contact: arianna.magagna@studio.unibo.it

**Beatrice Ciancarella**  
BSc Physics - University of Trieste  
MSc Science of Climate — University of Bologna  
📫 Contact: beatrice.ciancarella@studio.unibo.it

**Sveva Flocco**  
BSc Maths - University of Rome  
MSc Science of Climate — University of Bologna  
📫 Contact: sveva.flocco@studio.unibo.it

---

## 📌 Related Project

Check out our EOF time series processing notebook here:  
🔗 [EOF-time-series](https://github.com/ariannamagagna/EOF-time-series)


