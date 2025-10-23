# 🌾 Mini-Project-3
**Project Title**: *Predicting Crop Production Based on Agricultural Data*

---

**Domain:** Agriculture

**Tools Used:** Streamlit, Pandas, Plotly, SQL, Google colab, Machine learning(Regression)

---
## 🚀 Project Description

A **Streamlit-based interactive dashboard** to predict crop production using machine learning models. Users can explore historical crop production trends, make predictions for future years, and visualize model performance.

---

## 🔹 Features

- **Multilingual Crop & Region Selection**: Choose country/region and crop type.
- **Predict Crop Production**: Input area harvested and yield to predict production (in tons) using multiple ML models.
- **Historical Trends**: Plot historical production data with predicted values and projection lines.
- **Model Accuracy Summary**: Display R², RMSE, and MAE for all trained models.
- **Compare Models**: Visualize predictions from multiple models in a single plot.
- **Interactive Charts**: Plotly visualizations for trend analysis and actual vs predicted comparison.

---

## 🔹 ML Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regressor (SVR)
- K-Nearest Neighbors (KNN)

> All models are trained using **log-transformed production values** and saved in pickle (`.pkl`) format. Predictions are converted back to actual production (tons).

---

## 🔹 Installation

1. Clone the repository:

```bash
git clone <repo-url>
cd <repo-folder>
