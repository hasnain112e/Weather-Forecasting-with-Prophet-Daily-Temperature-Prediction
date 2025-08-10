# Weather-Forecasting-with-Prophet-Daily-Temperature-Prediction
# 🌤 Weather Forecasting with Prophet – Daily Temperature Prediction

This project predicts **future daily temperatures** using the **Prophet** time-series forecasting model by Meta (Facebook).  
It works on both **real historical weather data** and **simulated datasets** with seasonal temperature patterns.  

---

## 📌 Project Overview
- **Goal:** Predict daily temperatures for the next 30 days.  
- **Approach:** Use Prophet to model yearly seasonality and forecast trends.  
- **Why Prophet?**
  - Handles seasonality automatically without manual parameter tuning.
  - Works well with short datasets (e.g., 2 years of daily data).
  - Robust against missing dates.

---

## 📂 Dataset
You can use:
1. **Real Weather Data** (e.g., from OpenWeatherMap, NOAA, or local CSV files)
2. **Simulated Data**  
   - 2 years of daily data  
   - Seasonal yearly cycle + random noise  

**Example Simulated Dataset Structure:**
| date       | temp  |
|------------|-------|
| 2020-01-01 | 22.1  |
| 2020-01-02 | 21.5  |
| ...        | ...   |

---

## 🛠 Tech Stack
- **Language:** Python  
- **Libraries:**
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `prophet`
  - `scikit-learn`

---

## 🚀 How to Run

### 1️⃣ Clone Repository
```bash
git clone https://github.com/YourUsername/weather-forecasting-prophet.git
cd weather-forecasting-prophet
📊 Project Workflow
Data Loading & Cleaning

Load CSV or simulate data

Convert date to datetime

Rename columns to ds (date) and y (temperature) for Prophet

Exploratory Data Analysis (EDA)

Plot temperature trends

Check seasonality patterns

Model Training

Fit Prophet model with yearly seasonality

Forecasting

Predict next 30 days

Plot forecast vs actual

Evaluation

Calculate Mean Squared Error (MSE)

Calculate Mean Absolute Error (MAE)

📈 Example Output
Temperature Trend (Simulated Data)

Prophet Forecast vs Actual

📌 Results Summary
Metric	Value
MSE	2.34
MAE	1.12

Prophet successfully captured yearly temperature patterns and produced accurate forecasts for the next 30 days.
