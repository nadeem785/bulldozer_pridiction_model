# Bulldozer Price Prediction Model 🚜📈

This project is a **Machine Learning model** that predicts the **sale price of bulldozers** using historical auction data.  
It is inspired by the Kaggle competition **"Blue Book for Bulldozers"**.

---

## 📌 Project Overview
- Goal: Predict the future sale price of bulldozers given their usage, equipment type, and configuration.  
- Approach: Train a **regression model** on tabular data with time-dependent features.  
- Dataset: Historical auction results (train + valid + test).  

---

## ⚙️ Tech Stack
- **Python**
- **Pandas** – data cleaning & preprocessing  
- **NumPy** – numerical computations  
- **Matplotlib / Seaborn** – visualization  
- **Scikit-learn** – feature engineering & baseline models  
- **XGBoost / RandomForest** – regression models  

---

## 🛠️ Features
1. **Data Preprocessing**
   - Handling missing values  
   - Encoding categorical variables  
   - Feature engineering with dates  

2. **Model Training**
   - Baseline regression model  
   - Hyperparameter tuning with GridSearchCV / RandomizedSearchCV  

3. **Evaluation**
   - Root Mean Squared Log Error (**RMSLE**) metric  
   - Feature importance analysis  

---

## 📊 Results
- Best model: **XGBoost Regressor**  
- Evaluation metric: **RMSLE ~ 0.25** (example, update with your actual score)  

---

## 🚀 How to Run
```bash
# Clone repo
git clone https://github.com/your-username/bulldozer_prediction_model.git
cd bulldozer_prediction_model

# Install dependencies
pip install -r requirements.txt

# Run notebook / script
jupyter notebook Bulldozer_Prediction.ipynb
