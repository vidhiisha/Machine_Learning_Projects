# 🚖 Predict Amount of Taxi  

A machine learning project that predicts taxi fare amounts based on trip details, including pickup/dropoff coordinates, timestamps, and passenger count. This project demonstrates **end-to-end data science workflow** with data cleaning, feature engineering, multi-model training, evaluation, and visualization.  

---

## 🔍 Multi-Model Training and Comparison for Taxi Fare Prediction  

This project evaluates and compares multiple regression models to identify the most accurate model for predicting taxi fares:  

- **Linear Regression**  
- **Decision Tree Regressor**  
- **Random Forest Regressor**  
- **Gradient Boosting Regressor**  

The best-performing model is selected based on **R² score, MAE, and RMSE** metrics.  

---

---

## 📊 Dataset Information  

| Column                     | Description                              |
|----------------------------|------------------------------------------|
| `unique_id`                | Unique identifier for each trip         |
| `amount`                   | Taxi fare amount (target variable)      |
| `date_time_of_pickup`      | Pickup timestamp                        |
| `longitude_of_pickup`      | Pickup longitude                        |
| `latitude_of_pickup`       | Pickup latitude                         |
| `longitude_of_dropoff`     | Dropoff longitude                       |
| `latitude_of_dropoff`      | Dropoff latitude                        |
| `no_of_passenger`          | Number of passengers                   |

---

## 🧠 Key Features  

- **Feature Engineering**:  
  - Trip distance calculation using Haversine formula  
  - Extracted date and time components (hour, day, month, weekday)  

- **Preprocessing**:  
  - Missing value handling  
  - Outlier detection and removal  
  - Data scaling using `StandardScaler`  

- **Modeling**:  
  - Trained and compared multiple ML models  
  - Evaluated using **MAE, RMSE, R²**  
