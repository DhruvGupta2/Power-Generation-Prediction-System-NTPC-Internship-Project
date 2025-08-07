# 🏭 Power Generation Optimization System – NTPC Internship Project

This project was developed during my internship at NTPC (National Thermal Power Corporation), where I worked with real power plant data to build a machine learning model that predicts and optimizes power output (**GG4_MW**) using operational parameters.

---

## 🔍 Project Overview

- **🧠 Goal**: Predict and optimize power generation (GG4_MW) using real-time plant sensor data.
- **📊 Data**: 108 operational features (temperatures, pressures, flow rates, etc.)
- **⚙️ Model**: Random Forest Regressor (R² = 0.997)
- **🧪 Optimization**: Bayesian Optimization to suggest ideal input setpoints
- **📈 Evaluation**: RMSE, MAE, MAPE, cross-validation

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
- Evaluated using **cross-validation** with R² and RMSE

---

## 🧠 Optimization Logic

- Implemented **Bayesian Optimization** to find optimal input setpoints
- Goal: **Maximize GG4_MW** or **Minimize Heat Rate**
- Predicted best configuration using trained model

---

## 📁 Repository Structure

```
├── notebook.ipynb          # Jupyter Notebook with full pipeline
├── README.md               # Project summary and details
├── requirements.txt        # Python dependencies (optional)
```

---

## 📌 Future Work

- Deploy as a **Streamlit Dashboard** or Flask API
- Add real-time data ingestion support (SCADA integration)
- Implement feedback loop for model retraining

---

## 🧰 Technologies Used

- Python (Pandas, NumPy, Scikit-learn)
- Matplotlib, Seaborn
- Bayesian Optimization (bayes_opt library)
- Jupyter Notebook

---

## 📜 License

This project is for educational/research use only.