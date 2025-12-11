# INFO7390_Teaching-Data-Science-Concepts_TimeSeries
Shihan Qiao_002409794_assignment
# 📘 Time Series Forecasting Teaching Module  
### Using ARIMA, Prophet, and LSTM for S&P 500 Forecasting  
**Author:** Shihan Qiao  
**Course:** INFO 7390 – Advanced Data Science  
**Purpose:** Teaching Module + Final Project

---

## 🧠 Project Overview

This repository contains a complete instructional module that teaches three major paradigms of time-series forecasting:

1. **ARIMA** – classical statistical modeling  
2. **Prophet** – trend/seasonality decomposition  
3. **LSTM** – nonlinear deep learning sequence modeling  

The project is designed as a **progressive, hands-on learning experience** for graduate students.  
It includes conceptual explanations, mathematical deep dives, implementation analysis, debugging guidance, visual examples, and structured exercises.

This module serves both as a **teaching resource** and a **technical demonstration** of forecasting on the S&P 500 index using real market data (2020–2024).

---

## 📂 Repository Structure

├── notebook/
│ ├── TimeSeries_Tutorial.ipynb # Full interactive tutorial
│ ├── ARIMA_Prophet_LSTM_Examples.ipynb # Standalone demonstration files
│
├── docs/
│ ├── TeachingDocument.docx # Full expanded teaching document
│ ├── TeachingDocument.pdf # (optional) PDF version
│
├── figures/
│ ├── ARIMA_diagram.png
│ ├── Prophet_diagram.png
│ ├── LSTM_diagram.png
│
├── data/
│ ├── sp500_2020_2024.csv # Exported from yfinance (optional)
│
└── README.md

---

## 📊 Forecasting Models Covered

### **1. ARIMA**
- Classical time-series model  
- Requires stationarity and differencing  
- Captures short-term autocorrelation  
- Limitations: weak on strong trends or structural breaks  

### **2. Prophet**
- Trend + seasonality + holiday decomposition  
- Piecewise linear trend with changepoint detection  
- Robust to missing data and outliers  
- Highly interpretable and industry-friendly  

### **3. LSTM**
- Neural network for sequence modeling  
- Learns nonlinear dependencies  
- Powerful but requires careful preprocessing  
- Supports multi-step forecasting  

---

## 🖼 Illustrative Figures

Below are conceptual diagrams auto-generated for this module:

### **ARIMA – Conceptual Structure**
![ARIMA](figures/ARIMA_diagram.png)

### **Prophet – Trend & Seasonality Decomposition**
![Prophet](figures/Prophet_diagram.png)

### **LSTM – Memory Cell Structure**
![LSTM](figures/LSTM_diagram.png)

---

## 🚀 Getting Started

### **Install Dependencies**

```bash
pip install yfinance pandas numpy matplotlib statsmodels prophet tensorflow scikit-learn
