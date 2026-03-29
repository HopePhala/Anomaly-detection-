# Machine Learning-Based Anomaly and Fraud Detection in Digital Financial Transactions

## 📌 Overview
This project focuses on detecting fraudulent transactions in digital financial systems using Machine Learning techniques. The study evaluates both supervised and unsupervised learning models to determine their effectiveness in identifying anomalies and fraud in credit card transaction data.

The project was implemented using a Google Colab notebook and trained on the Kaggle Credit Card Fraud Detection dataset.

## 🎯 Objectives
The main objectives of this project are to:

- Perform data preprocessing and feature preparation for fraud detection
- Handle class imbalance using SMOTE
- Apply and compare multiple Machine Learning models
- Evaluate model performance using fraud detection metrics

## 🧠 Machine Learning Models Used
This project compares the following models:

### Supervised Learning Models
- Random Forest
- XGBoost

### Unsupervised Learning Models
- Isolation Forest
- Autoencoders

## ⚙️ Methodology
The project followed these major steps:

1. **Data Loading and Inspection**
   - Loaded the Kaggle credit card fraud dataset into Google Colab
   - Inspected structure, features, and class distribution

2. **Data Cleaning**
   - Removed duplicate rows
   - Verified missing values

3. **Data Preprocessing**
   - Feature/target separation
   - Standardization using `StandardScaler`
   - Data balancing using **SMOTE**
   - Train-test split

4. **Model Training**
   - Trained supervised and unsupervised models

5. **Model Evaluation**
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - ROC-AUC Score

## 📊 Results Summary
The supervised learning models outperformed the unsupervised models.

| Model              | Accuracy | Recall | Precision | F1-Score | ROC-AUC |
|-------------------|----------|--------|-----------|----------|---------|
| Random Forest      | 0.999    | 0.999  | 0.998     | 0.999    | 0.999   |
| XGBoost            | 0.998    | 0.999  | 0.997     | 0.998    | 0.998   |
| Isolation Forest   | 0.605    | 0.225  | 0.953     | 0.369    | 0.6058  |
| Autoencoder        | 0.766    | 0.584  | 0.925     | 0.715    | 0.767   |

## 🏆 Key Findings
- **Random Forest** and **XGBoost** achieved the best performance
- Supervised learning performed significantly better than unsupervised learning
- **SMOTE** helped improve fraud detection performance by addressing class imbalance
- Unsupervised models were useful for anomaly detection, but had lower recall

## 🛠️ Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- TensorFlow / Keras
- imbalanced-learn (SMOTE)

## ▶️ How to Run the Project
1. Open the Google Colab notebook:
   https://colab.research.google.com/drive/1aW_KpLxeuH3O1HklSj5cvULMV7_PYC88?usp=sharing

2. Run the notebook step by step

3. Make sure the required libraries are installed:
   - pandas
   - numpy
   - scikit-learn
   - xgboost
   - tensorflow
   - imbalanced-learn
   - matplotlib

## 📁 Project Structure
fraud-detection-project/
│
├── fraud_detection_notebook.ipynb
├── README.md
└── dataset/ (optional if included)

## 📚 Dataset
This project uses the **Kaggle Credit Card Fraud Detection Dataset**, which contains anonymized transaction features and fraud labels.

## 👤 Author
**Mmamoloko Hope Phala**

## 🎓 Academic Context
This project forms part of an Honours research study in Computer Science and focuses on improving fraud detection in digital financial transactions using Machine Learning.

## 📎 Colab Notebook
https://colab.research.google.com/drive/1aW_KpLxeuH3O1HklSj5cvULMV7_PYC88?usp=sharing

## 📌 Future Improvements
Possible future enhancements include:

- Hybrid fraud detection models
- Real-time fraud detection systems
- Explainable AI for fraud prediction
- Deployment as a web-based fraud detection tool
