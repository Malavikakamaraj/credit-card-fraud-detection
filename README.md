# 💳 Credit Card Fraud Detection

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Overview

This project focuses on detecting **fraudulent credit card transactions** using machine learning techniques.
It addresses the challenge of **highly imbalanced data**, where fraudulent transactions are much rarer than normal ones.

The goal is to build a reliable classification model that can accurately identify fraud cases while minimizing false positives.

---

## 🚀 Features

* 📊 Data preprocessing and cleaning
* 📉 Handling imbalanced datasets
* 🤖 Machine learning model training
* 📈 Evaluation using precision, recall, F1-score, and ROC-AUC
* 📦 Clean and modular project structure

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn

---

## 📊 Dataset

The dataset contains anonymized credit card transactions.

* **Class 0** → Legitimate transaction
* **Class 1** → Fraudulent transaction

⚠️ This dataset is highly imbalanced, making it a challenging classification problem.

📥 Download dataset from:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
pip install -r requirements.txt
```

---

## ▶️ Usage

### Train Model

```bash
python src/train_model.py
```

### Evaluate Model

```bash
python src/evaluate.py
```

---

## 📉 Evaluation Metrics

Since accuracy alone is not sufficient for imbalanced datasets, we use:

* Precision
* Recall
* F1-score
* ROC-AUC
* Confusion Matrix

---

## 📈 Models Used

* Logistic Regression
* Random Forest *(optional upgrade)*
* Isolation Forest *(for anomaly detection)*

---

## 🔮 Future Improvements

* Apply SMOTE for better class balancing
* Hyperparameter tuning
* Deploy as a web app (Streamlit/Flask)
* Real-time fraud detection API

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.
