# Advanced Time Series Forecasting with Hierarchical Temporal Memory (HTM)

This project implements and compares Hierarchical Temporal Memory (HTM) against a strong deep-learning baseline (LSTM) for complex multivariate time series forecasting.

HTM is a biologically inspired sequence learning algorithm modeled after the mammalian neocortex. This project evaluates its effectiveness on synthetic data with strong seasonality, trends, and regime shifts — conditions where HTM often shows strong adaptability.

---

# 🚀 Project Overview

### Objective
To build an end-to-end forecasting system that:

1. Generates a complex multivariate time series dataset (≥12,000 points)
2. Implements a functional HTM-like sequence memory model
3. Trains a baseline LSTM model for comparison
4. Evaluates both models using RMSE, MAE, and Directional Accuracy
5. Provides insights on HTM behavior, adaptability, and prediction quality

---

# 📊 Dataset Description

The dataset is synthetically generated to ensure:

- Multi-seasonality  
- Nonlinear trend  
- Regime shifts around 65% of the dataset  
- Multivariate dependencies across three channels:  
  - y1 → primary target  
  - y2, y3 → correlated helper features  

Example equation for y1:
