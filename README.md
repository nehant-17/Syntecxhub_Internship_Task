# Syntecxhub_Internship_Task

# Task 1 : House Price Prediction

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

# Task 2 :  Spam Detection

A Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)**. This project demonstrates a complete ML workflow including data preprocessing, text cleaning, feature extraction, model training, evaluation, and prediction.

---

## 🚀 Project Overview

The goal of this project is to build a machine learning model capable of detecting whether a message is spam or not.

The project uses various text preprocessing techniques such as tokenization, stopword removal, punctuation removal, and text vectorization to improve model performance.

---

## ✨ Features

- Data Cleaning and Preprocessing
- Text Normalization
- Removal of Punctuation and Stopwords
- Tokenization using NLTK
- Feature Extraction using TF-IDF
- Machine Learning Model Training
- Spam/Ham Message Classification
- Model Evaluation and Performance Analysis

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- String Library

---

## 📂 Project Structure

```
Spam_Detection/
│
├── spam_ham_dataset.csv
├── Project_2.pynb
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

The dataset used in this project contains E-mails labeled as:

- **Spam** → Unwanted promotional or fraudulent messages.
- **Ham** → Legitimate messages.

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Syntecxhub_Internship_Task.git
```

### 2. Navigate to the Project Directory

```bash
cd Syntecxhub_Internship_Task
```

---

## 📦 Install Dependencies

Install all required libraries using:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install pandas numpy scikit-learn nltk
```

---

## 🔄 Data Preprocessing Steps

1. Convert text to lowercase.
2. Remove punctuation marks.
3. Tokenize text into words.
4. Remove stopwords.
5. Perform stemming/lemmatization (if used).
6. Convert text into numerical features using TF-IDF Vectorizer.

---

## 🤖 Model Training

The processed text data is used to train a machine learning classifier for spam detection.

Typical workflow:

- Data Splitting
- Feature Extraction (TF-IDF)
- Model Training
- Model Evaluation
- Prediction on New Messages

---

## 📈 Model Performance

The model performance is evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision Score
- Recall Score
- F1 Score

Example Results:

| Metric | Score |
|---------|-------|
| Precision_score | 0.9563758389261745 |
| Recall_score | 0.9726962457337884 |
| F1_Score | 0.9644670050761421 |

> Note: Performance may vary depending on preprocessing techniques and model selection.

---


---

## 🎯 Conclusion

This project demonstrates how Natural Language Processing (NLP) and Machine Learning can be combined to effectively identify spam messages and improve communication security.


# Task 3 : Customer Segmentation


A Machine Learning project that segments customers into different groups using the **K-Means Clustering** algorithm. This project demonstrates an unsupervised learning workflow including data preprocessing, exploratory data analysis (EDA), feature selection, clustering, visualization, and model evaluation.

---

## 🚀 Project Overview

The goal of this project is to group customers with similar purchasing behavior into distinct segments. These customer segments help businesses understand customer patterns and develop targeted marketing strategies.

The project uses the **K-Means Clustering** algorithm from Scikit-learn along with data preprocessing and visualization techniques to identify meaningful customer groups.

---

## ✨ Features

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Selection
- Data Scaling
- K-Means Clustering
- Elbow Method for Optimal Number of Clusters
- Customer Segment Visualization
- Cluster Analysis and Interpretation

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

```
Customer_Segmentation/
│
├── customer_segmentation.csv
├── Project_3
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

The dataset contains customer information used for segmentation.

Typical features include:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

These features are used to identify customers with similar purchasing behaviors.

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Syntecxhub_Internship_Task.git
```

### 2. Navigate to the Project Directory

```bash
cd Syntecxhub_Internship_Task
```

---

## 📦 Install Dependencies

Install all required libraries using:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🔄 Data Preprocessing Steps

1. Load the dataset.
2. Check for missing values.
3. Select relevant features.
4. Scale the data using StandardScaler.
5. Apply the Elbow Method to determine the optimal number of clusters.
6. Train the K-Means Clustering model.
7. Visualize the customer segments.

---

## 🤖 Model Training

The project uses the **K-Means Clustering** algorithm to divide customers into multiple groups based on their characteristics.

Workflow:

- Data Preprocessing
- Feature Scaling
- Elbow Method
- K-Means Model Training
- Cluster Prediction
- Data Visualization

---

## 📈 Model Performance

The clustering model is evaluated using:

- Elbow Method
- Inertia (Within-Cluster Sum of Squares)
- Cluster Visualization
- Customer Segment Analysis

These metrics help determine the optimal number of clusters and assess clustering quality.

---

## 📊 Visualization

The project includes visualizations such as:

- Elbow Curve
- Customer Cluster Scatter Plot
- Cluster Distribution
- Feature Relationship Graphs

---




---

