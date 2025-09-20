# 🧱 BrickByBrick - Bay Area Housing Price Forecasting with ML & Tableau

**BrickByBrick** is a machine learning project that predicts monthly housing prices across the San Francisco Bay Area. Using Zillow's ZHVI data and macroeconomic indicators (via the FRED API), the project explores time-based, lagged, and rolling-window features to forecast home value trends and visualizes them through a dynamic Tableau dashboard.

---

## 📈 Features

- 📊 Forecasts 12-month ZHVI trends using historical and engineered features  
- 🔁 Adds lagged & rolling features for richer time-series learning  
- 🧠 Compares multiple models (Linear, Ridge, Random Forest, etc.) using RMSE  
- 📅 Includes month dummy variables for seasonality effects  
- 📦 Automates model selection and full-data retraining  
- 🖼️ Visualized results via Tableau dashboard  
- 📁 Outputs forecasts and feature data to clean `.csv` files for analysis  

---

## 🛠️ Tech Stack

- Python (Pandas, scikit-learn, matplotlib)  
- Jupyter/Colab Notebooks  
- FRED API (via `fredapi`)  
- Tableau (for final dashboard)  
- GitHub (version control)  
- `joblib` (for saving model state)

---

## 🧪 Setup Instructions (Colab-based)

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Basim415/BrickByBrick.git
   cd BrickByBrick
