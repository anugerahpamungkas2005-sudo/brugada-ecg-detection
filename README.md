# Brugada Syndrome Detection using Logistic Regression with ADASYN

## 📌 Overview

This project aims to detect Brugada Syndrome using ECG-derived features and machine learning techniques.

## ⚙️ Methodology

* Logistic Regression
* ADASYN for handling class imbalance
* StandardScaler for preprocessing
* Threshold tuning for performance optimization

## 📊 Results

* Accuracy: 0.813
* ROC-AUC: 0.817
* Recall: 0.706
* F1-score: 0.585

The model successfully detected 12 out of 17 Brugada cases.

## 🧠 Key Insights

* Prioritizing recall is critical in medical diagnosis
* ADASYN improves minority class detection
* Logistic Regression provides interpretability

## 📁 Files

* notebook.ipynb → main code
* model.pkl → trained model
* threshold.pkl → optimal threshold

## ▶️ How to Use

1. Clone repository:

```
git clone https://github.com/anugerahpamungkas2005-sudo/brugada-ecg-detection
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the notebook:
   Open `notebook.ipynb` using Google Colab or Jupyter Notebook

4. (Optional) Use pre-trained model:

```
import joblib

model = joblib.load("model/brugada_logistic_regression_adasyn.pkl")
threshold = joblib.load("model/brugada_lr_threshold_adasyn.pkl")
```

## 📚 Dataset

PhysioNet - Brugada-HUCA Dataset

## 👨‍💻 Authors

* Amalia Putri
* Anugerah Pamungkas
