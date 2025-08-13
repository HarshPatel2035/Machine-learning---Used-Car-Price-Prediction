# 🚗 Used Car Price Prediction (Regression) – Machine Learning Project

## 📌 Overview
This project predicts the **selling price of used cars** based on various features such as year of manufacture, mileage, fuel type, seller type, transmission, and more.  
The model uses **XGBoost Regression**, a powerful gradient boosting algorithm, to provide accurate and reliable predictions.

## 🎯 Objective
The main goal of this project is to:
- Build a machine learning model that predicts car prices with high accuracy.
- Understand the impact of different features on the final price.
- Deploy the trained model for practical usage (optional future enhancement).

## 📊 Dataset
The dataset contains information about used cars, including:
- **Car Name** – Model name of the car.
- **Year** – Manufacturing year.
- **Selling Price** – Target variable (price in lakhs).
- **Present Price** – Price when the car was new.
- **Kms Driven** – Total kilometers driven.
- **Fuel Type** – Petrol/Diesel/CNG.
- **Seller Type** – Dealer/Individual.
- **Transmission** – Manual/Automatic.
- **Owner** – Number of previous owners.

> The dataset was preprocessed to handle missing values, encode categorical variables, and scale numerical features.

## 🛠 Tech Stack
- **Programming Language:** Python
- **Libraries & Frameworks:**
  - pandas, numpy – Data processing
  - matplotlib, seaborn – Data visualization
  - scikit-learn – Preprocessing, train-test split, evaluation
  - XGBoost – Machine learning regression model
  - Jupyter Notebook – Development environment

## 📈 Workflow
1. **Data Collection** – Loaded dataset for used cars.
2. **Data Preprocessing** – Cleaned and transformed data for modeling.
3. **Exploratory Data Analysis (EDA)** – Visualized data patterns and correlations.
4. **Feature Engineering** – Encoded categorical variables and handled outliers.
5. **Model Building** – Implemented XGBoost Regression.
6. **Model Evaluation** – Evaluated model performance using R² Score, MAE, and RMSE.
7. **Prediction** – Predicted car prices for new/unseen data.

## 📊 Model Performance
| Metric      | Score |
|-------------|-------|
| R² Score    | 0.89  |
| MAE         | 4099.05 |
| RMSE        | 6238.48  |

## 📂 Project Structure
├── Used_Car_Price_Prediction_using_XGBoost.ipynb # Main Jupyter Notebook
├── README.md # Project documentation
├── car.csv # Data for training
├── used_car_report.html # Data Report
