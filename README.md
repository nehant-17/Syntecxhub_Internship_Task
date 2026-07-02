# 👥 Customer Segmentation

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
├── dataset/
│ └── Mall_Customers.csv
│
├── notebooks/
│ └── Customer_Segmentation.ipynb
│
├── models/
│ └── kmeans_model.pkl
│
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
