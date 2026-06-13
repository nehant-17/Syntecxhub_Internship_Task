# Syntecxhub_Internship_Task

# Task 1

A Machine Learning project that predicts house prices using the California Housing dataset. This project demonstrates a complete ML workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and model saving.

---

## 📌 Project Overview

The goal of this project is to build a regression model capable of predicting house prices based on various housing-related features such as location, number of rooms, population, households, and more.

The project uses **Linear Regression** from Scikit-learn and includes data cleaning, feature transformation, and visualization techniques to improve model performance.

---

## 🚀 Features

- Data Cleaning and Missing Value Handling
- Exploratory Data Analysis (EDA)
- Correlation Heatmap Visualization
- Log Transformation of Numerical Features
- Feature Engineering
- Categorical Feature Encoding
- Linear Regression Model Training
- Model Evaluation using RMSE and R² Score
- Actual vs Predicted Price Visualization
- Model Serialization using Joblib

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

```text
House-Price-Prediction/
│
├── housing.csv
├── Project_1.pynb
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

The project uses the California Housing dataset containing information such as:

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity
- Median House Value (Target Variable)

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/House-Price-Prediction.git
cd House-Price-Prediction
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python Project_1.pynb
```

---

## 📈 Model Performance

| Metric | Value |
|----------|----------|
| RMSE | 67305.502 |
| R² Score | 0.6687 |

### Interpretation

- RMSE indicates the average prediction error in house prices.
- R² Score of 0.6359 means the model explains approximately 63.59% of the variance in housing prices.

---

## 🔍 Feature Engineering

The following transformations were applied:

### Log Transformations

- Total Rooms
- Total Bedrooms
- Population
- Households

### New Features Created

- Bedroom Ratio
- Household Rooms

### Categorical Encoding

- Ocean Proximity (One-Hot Encoding)

---

## 📉 Visualizations

The project generates:

### Correlation Heatmap

Used to understand relationships between numerical features.

### Actual vs Predicted Prices

Scatter plot comparing model predictions with actual housing prices.

---
