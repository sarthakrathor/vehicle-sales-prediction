# Vehicle Sales Prediction Model

Predicts customer car purchase amounts based on demographic and financial data.

## 🛠️ Installation
```bash
git clone https://github.com/sarthakrathor/vehicle-sales-prediction.git
cd vehicle-sales-prediction
pip install -r requirements.txt
```

## 📊 Results
| Model          | MAE   | RMSE  | R² Score |
|----------------|-------|-------|----------|
| Linear Regression | 2500 | 3200  | 0.82     |
| XGBoost        | 1800  | 2400  | 0.89     |


## 📝 Methodology
1. **Data Preprocessing**:
   - Outlier handling with IQR
   - One-hot encoding for categorical variables
   - StandardScaler for numerical features

2. **Key Features**:
   - `debt_to_income_ratio`
   - `savings = net worth - credit card debt`

3. **Model Selection**:
   - XGBoost outperformed others with 89% R² score
