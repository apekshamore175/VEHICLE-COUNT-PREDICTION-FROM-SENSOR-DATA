# 🚗 Vehicle Count Prediction from Sensor Data

A Machine Learning project that predicts vehicle traffic volume using weather and time-based sensor data. The project performs data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison of multiple regression algorithms.

---

## 📌 Project Overview

Traffic prediction helps in smart city planning, traffic management, route optimization, and congestion control. This project uses the **Metro Interstate Traffic Volume** dataset to predict the number of vehicles on a road based on weather conditions and time-related features.

---

## 🎯 Objectives

- Analyze traffic volume patterns.
- Perform data cleaning and preprocessing.
- Create time-based features from date and time.
- Train multiple machine learning regression models.
- Compare model performance using evaluation metrics.
- Visualize traffic trends and feature importance.

---

## 📂 Dataset

**Dataset:** Metro Interstate Traffic Volume

Source: Kaggle

The dataset contains:

- Traffic Volume
- Temperature
- Rainfall
- Snowfall
- Cloud Coverage
- Holiday
- Weather Condition
- Weather Description
- Date & Time

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Feature Engineering
5. Exploratory Data Analysis (EDA)
6. Correlation Analysis
7. Feature Selection
8. Train-Test Split
9. Model Training
10. Model Evaluation
11. Model Comparison
12. Feature Importance Analysis
13. Actual vs Predicted Visualization

---

## 📈 Exploratory Data Analysis

The project includes visualizations such as:

- Traffic Volume Distribution
- Average Traffic by Hour
- Average Traffic by Day of Week
- Monthly Traffic Analysis
- Weekday vs Weekend Traffic
- Rush Hour Analysis
- Weather Impact on Traffic
- Correlation Heatmap
- Feature Importance
- Actual vs Predicted Graph

---

## 🤖 Machine Learning Models

The following regression models were implemented:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

---

## 📏 Evaluation Metrics

Models were evaluated using:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

---

## 📊 Results

The trained models were compared using RMSE and R² Score.

Among the implemented models, **Random Forest Regressor** performed better than Linear Regression and XGBoost on this processed dataset.

> **Note:** The dataset became significantly smaller after removing rows with missing values, which affected overall model performance. Future improvements can be made using better missing-value handling techniques instead of dropping all null rows.

---

## 📁 Project Structure

```
Vehicle-Count-Prediction/
│
├── Vehicle_Count_Prediction.ipynb
├── Metro_Interstate_Traffic_Volume.csv
├── README.md
└── images/
```

---

## 🚀 Future Improvements

- Handle missing values using imputation instead of dropping rows.
- Perform hyperparameter tuning.
- Add more traffic-related features.
- Deploy the model using Flask or Streamlit.
- Build an interactive traffic prediction dashboard.
- Use larger and cleaner datasets for improved accuracy.

---

## 💡 Applications

- Smart Traffic Management
- Smart Cities
- Traffic Congestion Prediction
- Urban Planning
- Intelligent Transportation Systems

---

## 👨‍💻 Author

**Apeksha**

IT Engineering Student

Machine Learning | Data Science | Web Development

---

## ⭐ If you found this project useful, don't forget to Star the repository!
