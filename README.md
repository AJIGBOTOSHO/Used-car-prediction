# Used-car-prediction

<img width="782" height="562" alt="image" src="https://github.com/user-attachments/assets/9d106690-0c84-4280-85fe-6e070621915d" /> 

# 🚗 Used Car Price Prediction — DSN Hackathon Project

> Predicting resale prices of used cars using data science, domain knowledge, and machine learning.

## 📌 Project Overview

This project builds a regression model to predict the selling price of used cars based on features like:
- Brand
- Age
- Mileage per year
- Accident history
- Clean title status
- Fuel type (Gas/Electric/Hybrid)

We achieved an RMSE of **$1,710** on validation using **Random Forest with GridSearchCV** — outperforming baseline models by ~4%.

## 📊 Key Insights (from EDA)
- ✅ **Clean title** adds ~18% value
- ✅ **Accident history** reduces price by ~22%
- ✅ **Electric vehicles** command a $8K–$12K premium
- ✅ **Car age** is the strongest negative predictor

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn (RandomForestRegressor, GridSearchCV)
- Matplotlib, Seaborn (EDA)
- CatBoost (tested, but RF won)

## 📂 Files Included
- `used_car_price_prediction_DSN_Hackathon.ipynb` — Full notebook with EDA, preprocessing, tuning
- `submission.csv` — Final predictions for submission
- `train.csv`, `test.csv` — Original datasets (if permitted)

## 🏆 Results
| Model | CV RMSE |
|-------|---------|
| Linear Regression | 0.55 |
| Decision Tree | 0.54 |
| Random Forest (untuned) | 0.53 |
| ✅ **Random Forest (tuned)** | 0.53 |

## 🙌 Acknowledgments
- DSN Hackathon organizers  
- Kaggle dataset sources (if used)  
- My team / mentor (if applicable)

## 📄 License
MIT © 2025 [Your Name]
