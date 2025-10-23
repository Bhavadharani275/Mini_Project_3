# 🌾 Mini-Project-3
**Project Title**: *Predicting Crop Production Based on Agricultural Data*

---

**Domain:** Agriculture  
**Tools Used:** Streamlit, Pandas, Plotly, SQL, Google Colab, Machine Learning (Regression)

---

## 🚀 Project Description

A **Streamlit-based interactive dashboard** to predict crop production using machine learning models.  
Users can explore historical crop production trends, make predictions for future years, and visualize model performance dynamically.

---

## 🔹 Features

- **📊 Data Exploration & Visualization** – Interactive plots showing trends of Area, Yield, and Production.  
- **🔮 Predict Crop Production** – Estimate production (in tons) using regression models.  
- **📈 Model Evaluation Dashboard** – R², RMSE, and MAE metrics for all models.  
- **🤖 Multi-Model Comparison** – Actual vs Predicted plots for all models in one Plotly graph.  
- **📆 Future Forecasting** – Predict crop production for any future year.

---

## 🔹 Approach

### 1️⃣ Data Cleaning and Preprocessing
- Handle missing data and standardize column metrics.  
- Filter and retain only relevant columns for analysis.  
- Encode categorical variables like `Area` and `Item` for modeling.

---

### 2️⃣ Exploratory Data Analysis (EDA)

#### 🔸 Crop Distribution
- **Crop Types**: Study the distribution of the `Item` column to identify the most and least cultivated crops.  
- **Geographical Distribution**: Analyze the `Area` column to determine regions with high agricultural activity.

#### 🔸 Temporal Analysis
- **Yearly Trends**: Explore changes in `Area harvested`, `Yield`, and `Production` over time.  
- **Growth Analysis**: Detect increasing or decreasing yield trends by crop or region.

#### 🔸 Environmental Relationships
- Even without explicit environmental data, infer links between **Area harvested** and **Yield** to understand how land utilization impacts productivity.

#### 🔸 Input–Output Relationships
- Examine correlations among **Area harvested**, **Yield**, and **Production** to reveal productivity dynamics.  

#### 🔸 Comparative Analysis
- **Across Crops**: Compare `Yield` values among different crops to find high- vs low-yield types.  
- **Across Regions**: Compare `Production` across regions to identify highly productive areas.

#### 🔸 Productivity Analysis
- Evaluate variations in `Yield` to pinpoint efficient crops and regions.  
- Calculate productivity ratios (`Production / Area harvested`) for verification.

#### 🔸 Outliers and Anomalies
- Detect anomalies in `Yield` or `Production` — such as sudden spikes or drops — and investigate possible causes (e.g., policy changes, weather impacts).

---

### 3️⃣ Task: Predicting Production
- **Target Variable:** `Production (tons)`  
- **Objective:** Predict production based on features such as Area, Yield, and Year using multiple regression models.

---

## 🔹 Visualizations

- 📈 Production Trend — Actual vs Predicted trends over years (toggle models via legend).
- 🎯 Actual vs Predicted Scatter — Evaluate how close predictions are to actual production.
- 🌱 Future Projections — Predict crop production for any future year.

---

## 🔹 ML Models Used

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Support Vector Regressor (SVR)  
- K-Nearest Neighbors (KNN)

> All models are trained using **log-transformed production values** and saved in pickle (`.pkl`) format.  
> Predictions are automatically converted back to actual production (in tons).

---

## 📂 Project Structure

- `Crop_Production.ipynb` — Main Colab notebook
- `FAOSTAT_data.xlsx` — Raw dataset
  
---

## 🔹 How to Run in Google Colab

1. **Open the Notebook**  
   Upload or open `Crop_Production.ipynb` in [Google Colab](https://colab.research.google.com/).

2. **Upload the Dataset**  
   - `FAOSTAT_data.xlsx` (raw dataset)

3. **Run All Cells**  
   The notebook performs:  
   - Data Cleaning & EDA  
   - Model Training  
   - Evaluation & Visualization  

4. **View Results**  
   - Interactive Plotly charts  
   - Model metrics table  
   - Actual vs Predicted plots  

---

## 👩‍💻 Author

**Bhavadharani**  
Mini-Project 3 — *Crop Production Prediction*  
