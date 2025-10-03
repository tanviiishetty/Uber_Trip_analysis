# Uber Trip Analysis & Forecasting

## 📌 Project Overview
This project analyzes **Uber trip data from January–February 2015** (NYC TLC FOIL dataset).  
The goal is to explore daily trip patterns and build predictive models to forecast future demand.

## 🗂 Dataset
- **Source**: NYC Taxi & Limousine Commission (FOIL request)  
- **File used**: `uber_jan_feb_foil.csv`  
- **Columns**:
  - `date`: Trip date  
  - `dispatching_base_number`: Base company code  
  - `active_vehicles`: Number of vehicles active that day  
  - `trips`: Number of trips completed  
  - Derived features: `dayofweek`, `day`, `month`

## ⚙️ Tools & Libraries
- Python, Pandas, NumPy  
- Matplotlib, Seaborn (visualization)  
- Scikit-learn (Random Forest)  
- Statsmodels (Holt-Winters Forecasting)  
- VS Code, Jupyter Notebook  

## 🔍 Exploratory Data Analysis (EDA)
- Trip trends over time  
- Peak days and weekdays  
- Base-wise contribution analysis  
- Visualization of demand patterns  

## 🤖 Machine Learning & Forecasting
1. **Random Forest Regressor**  
   - Predict daily trips based on date features  
   - Evaluated with MSE & R²  
2. **Holt-Winters Exponential Smoothing**  
   - Time-series forecasting with trend & seasonality  
   - Forecasts next 7 days demand  
   - Evaluated with MAE & RMSE  

## 📊 Key Insights
- Trip demand varies strongly by **day of week** (weekdays higher than weekends).  
- January shows lower demand compared to February.  
- Holt-Winters captured weekly seasonality well, achieving reliable short-term forecasts.  

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone <your-repo-link>
   cd UberTripAnalysis
