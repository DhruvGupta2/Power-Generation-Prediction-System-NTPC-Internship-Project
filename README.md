# 🏭 Power Generation Optimization System – NTPC Internship Project

This project was developed during my internship at NTPC (National Thermal Power Corporation), where I worked with real power plant data to build a machine learning model that predicts and optimizes power output (**GG4_MW**) using operational parameters.

---

## 🔍 Project Overview

- **🧠 Goal**: Predict and optimize power generation (GG4_MW) using real-time plant sensor data.
- **📊 Data**: 108 operational features (temperatures, pressures, flow rates, etc.)
- **⚙️ Model**: Random Forest Regressor (R² = 0.997)
- **📈 Evaluation**: RMSE, MAE, MAPE

---

## 🧹 Data Preprocessing

- Handled missing values via **mean imputation**
- Converted object-type columns to **float/int**
- Removed **duplicates** and **infinite values**
- Conducted **feature engineering and selection** (e.g., SelectKBest)
- Visualized trends using **correlation heatmaps, boxplots, and histograms**
- Split data into **training and testing sets (80-20)**

---

## 🤖 Model Training

- Used **RandomForestRegressor** to predict GG4_MW from input variables
- Achieved **R² Score: 0.997**, **RMSE: 1.51**

---

## 📁 Repository Structure

```
├── Power Generation Prediction.ipynb          # Jupyter Notebook with full pipeline
├── README.md                                  # Project summary and details

```

---

## 📌 Future Work

- Deploy as a **Streamlit Dashboard** or Flask API
- Add real-time data ingestion support (SCADA integration)
- Implement feedback loop for model retraining

---

## 🧰 Technologies Used

- Python (Pandas, Scikit-learn)
- Matplotlib, Seaborn
- Jupyter Notebook

---
