# 🏠 Tehran House Price Prediction

A data science project using machine learning models to predict housing prices in Tehran based on features like area, rooms, location, and more.

## 📁 Dataset
Source: `tehranhouses.csv` — contains various features such as area (in sqm), rooms, district, year built, and price.

## 📊 Models Compared

- Linear Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regressor (SVR)
- XGBoost Regressor
- MLP Regressor (Neural Network)

## 🧪 Evaluation Metrics

Each model was evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## 📌 Results (Sample)

| Model            | R² Score | MAE     | RMSE   |
|------------------|----------|---------|--------|
| Random Forest    | 0.87     | 1.1e+8  | 1.8e+8 |
| XGBoost          | 0.86     | 1.2e+8  | 1.9e+8 |
| Linear Regression| 0.68     | 2.0e+8  | 3.0e+8 |

✅ Best performance: **Random Forest** and **XGBoost**
## 📊 Model Comparison

The following bar chart shows the R² score of the best-performing models in predicting house prices in Tehran:
<img width="2000" height="1200" alt="model_comparison_r2_real" src="https://github.com/user-attachments/assets/6ec9748c-acce-426e-9b3f-4ce5150c9e3b" />

## 📌 Tools Used
- Python
- Pandas, Seaborn, Matplotlib
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 🇮🇷 پروژه پیش‌بینی قیمت مسکن تهران

در این پروژه با استفاده از الگوریتم‌های یادگیری ماشین، قیمت خانه‌های تهران بر اساس مشخصاتی مانند متراژ، منطقه، سال ساخت و ... پیش‌بینی شده است.

📌 دقت بالاتر مربوط به مدل‌های **جنگل تصادفی (Random Forest)** و **XGBoost** است.

