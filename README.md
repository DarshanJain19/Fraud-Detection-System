# Fraud-Detection-System
🔍 Overview
Credit card fraud detection is crucial in modern banking systems. This project aims to detect fraudulent transactions using machine learning techniques. The dataset is highly imbalanced, so special handling such as SMOTE and evaluation with precision-recall metrics is applied.

🚀 Features

✔ Detect fraudulent transactions accurately
✔ Handles imbalanced dataset using SMOTE
✔ Includes EDA and data preprocessing
✔ Trains multiple ML models and compares performance
✔ Provides model evaluation reports and visualizations
✔ Can be integrated as an API for real-time prediction

📂 Project Structure
fraud-detection-system/
│
├── data/
│   ├── creditcard.csv (Dataset)
│
├── notebooks/
│   ├── Fraud_Detection_Model.ipynb
│
├── src/
│   ├── preprocess.py
│   ├── train.p
│   ├── utils.py
│   ├── predict.py
│
├── models/
│   ├── best_model.pkl
│
├── README.md
└── requirements.txt

📊 Dataset

This project uses the popular Credit Card Fraud Detection dataset
(Available on Kaggle)

Total records: 284,807

Fraud cases: 492 (0.172%) ⛔ Highly imbalanced

Features: 30 anonymized numerical variables + time + amount

Target:

0 → Normal transaction

1 → Fraudulent transaction

🛠️ Tech Stack
Technology	Purpose
Python	Main development
Pandas, NumPy	Data wrangling
Matplotlib, Seaborn	Visualization
Scikit-Learn	Machine Learning
SMOTE	Imbalanced data handling
XGBoost / Random Forest	Best performance


🤝 Contributions

Pull requests are welcome!
If you find a bug, open an issue.
