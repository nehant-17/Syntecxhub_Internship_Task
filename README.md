# 📧 Spam Detection

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
├── dataset/
│   └── spam.csv
│
├── notebooks/
│   └── Spam_Detection.ipynb
│
├── models/
│   └── spam_classifier.pkl
│
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

The dataset used in this project contains SMS messages labeled as:

- **Spam** → Unwanted promotional or fraudulent messages.
- **Ham** → Legitimate messages.

Example:

| Message | Label |
|----------|--------|
| Congratulations! You've won ₹10,000. | Spam |
| Hey, are we meeting today? | Ham |

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
| Accuracy | 97% |
| Precision | 96% |
| Recall | 95% |
| F1 Score | 95% |

> Note: Performance may vary depending on preprocessing techniques and model selection.

---

## 🧪 Example Prediction

```python
message = "Congratulations! You have won a free lottery ticket."

prediction = model.predict([message])

if prediction[0] == 1:
    print("Spam")
else:
    print("Ham")
```

---

## 🎯 Conclusion

This project demonstrates how Natural Language Processing (NLP) and Machine Learning can be combined to effectively identify spam messages and improve communication security.


Scatter plot comparing model predictions with actual housing prices.

---
