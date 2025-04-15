# Climate & Food Price Forecasting Project

### Forecasting Global Food Prices Based on Climate Trends using LSTM Neural Networks and Curve Fitting

---

##  Overview

This project explores the relationship between **climate change indicators** and **essential food prices** using time series analysis. The primary goal is to build and compare two predictive models:

- **Curve Fitting** – a simpler, traditional approach.
- **LSTM Neural Network** – a more powerful deep learning model suitable for temporal data.

After modeling, a **correlation analysis** is performed to investigate how trends in climate variables (like CO₂, CH₄ concentrations and temperature anomalies) relate to changes in food price indices over time.

---

## Motivation

As a physics graduate with a strong background in experimental data analysis, I wanted to transition into **data science** by applying my skills to **real-world, globally relevant data**. This project combines:

- Technical modeling
- Deep learning
- Statistical insight
- Data storytelling

---

## Data Sources

- [NASA Climate Data](https://science.nasa.gov/climate-change/)
- [FAO Food Price Index](https://www.fao.org/worldfoodsituation/foodpricesindex/en/)

---

## Techniques & Tools

### Libraries Used
- `pandas`, `numpy`, `matplotlib`, `seaborn` – for data handling and visualization
- `scikit-learn`, `scipy` – for curve fitting and evaluation
- `TensorFlow/Keras` – for building and training the LSTM model

### Data Analysis
- Time series cleaning and preprocessing
- Smoothing via Savitzky–Golay filter
- Normalization with `MinMaxScaler`

###  Modeling
- **Curve fitting** using exponential and polynomial trends
- **LSTM network** trained with `EarlyStopping` and regularization
- Model evaluation using `R²`, `MSE`

### Correlation
- Pearson correlation to quantify the relationship between climate variables and food prices

---

## Project Structure

```
Climate_Project/
│
├── Assets/                 # Raw datasets (from NASA and FAO)
├── Climate_Project.ipynb   # Main Jupyter Notebook with all analysis
└── README.md               # This file – project overview and instructions
```

## Key Findings

- LSTM models outperform traditional curve fitting in forecasting non-linear climate trends.
- Climate variables (e.g., CO₂, CH₄ levels, temperature anomalies) show visible trends over time.
- A positive correlation was observed between climate indicators and global food price indices.
- This suggests environmental shifts may influence economic conditions (e.g., food availability or cost).

---

## Skills Demonstrated

- Data preprocessing & cleaning
- Time series forecasting (Curve Fitting & LSTM)
- Deep learning (TensorFlow/Keras)
- Statistical correlation (Pearson)
- Scientific data interpretation
- Model evaluation (MSE, R²)
- Data storytelling & visualization

---
