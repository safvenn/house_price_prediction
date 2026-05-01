# 🏠 House Price Prediction Using Machine Learning

This project predicts house prices based on property features using Machine Learning.  
A Streamlit web application is built to allow users to input property details and get real-time price predictions.

---

# 📌 Project Overview

The goal of this project is to build a predictive model that estimates house prices using historical housing data.

This project includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Model Building
- Model Evaluation
- Streamlit Web Application for Predictions

---

# 🧰 Technologies Used

Programming Language:
- Python

Libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Deployment:
- Streamlit

---

# 📊 Dataset Description

The dataset contains housing-related information such as:

- Area (sqft)
- Number of Bedrooms
- Number of Bathrooms
- Location
- Parking Availability
- Property Age
- Price (Target Variable)

Dataset Type:
- Structured Tabular Data

---

# 🔍 Project Workflow

## 1️⃣ Data Cleaning

- Removed missing values
- Handled inconsistent entries
- Converted categorical values
- Verified data types

---

## 2️⃣ Exploratory Data Analysis (EDA)

Performed:

- Correlation analysis
- Distribution plots
- Outlier detection
- Feature relationships analysis

Visualizations created using:

- Matplotlib
- Seaborn

---

## 3️⃣ Feature Engineering

Created meaningful features such as:

- Price per square foot
- Property age groups
- Encoded categorical variables

---

## 4️⃣ Model Building

Machine Learning models tested:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Best Model Selected Based On:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

---

## 5️⃣ Model Evaluation

Evaluation Metrics Used:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

The selected model achieved reliable prediction accuracy on unseen test data.

---

# 🚀 Streamlit Web Application

A Streamlit app was created to make predictions interactive.

Users can:

- Enter house features
- Click Predict
- Get estimated house price instantly

---

## ▶️ Run Streamlit App

Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn streamlit
