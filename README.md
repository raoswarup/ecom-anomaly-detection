# 📦 E-commerce Anomaly Detection

This project aims to detect anomalies in e-commerce transactional data to identify fraudulent activities or abnormal behaviors. The model is trained using advanced machine learning techniques and deployed on Google Cloud for real-time monitoring.

---

## 📖 Project Overview
- **Objective:** Identify anomalies in e-commerce transactions using various anomaly detection techniques.
- **Dataset:** Public dataset sourced from [INSERT DATA SOURCE NAME].
- **Deployment:** Model is deployed on Google Cloud using a Flask API.

---

## 🛠️ Tech Stack
- **Programming Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, PyCaret, Flask
- **Modeling Techniques:**
  - Isolation Forest
  - One-Class SVM
  - Autoencoders
- **Deployment Platform:** Google Cloud (GCP)

---

## 📊 Data Preprocessing & Feature Engineering
1. **Data Cleaning:** Handling missing values, removing duplicates, and outlier detection.
2. **Feature Engineering:** Creating domain-specific features, scaling, and encoding.
3. **Class Imbalance Handling:** SMOTE, undersampling, or oversampling to balance class distribution.

---

## 🔥 Exploratory Data Analysis (EDA)
- Distribution of features
- Correlation heatmap
- Visualization of anomalies using PCA and t-SNE

---

## 🎯 Model Development & Evaluation
- **Model Selection:** Comparing various anomaly detection algorithms.
- **Cross-validation:** Using K-Fold CV for robustness.
- **Evaluation Metrics:**
  - Precision, Recall, and F1-Score
  - AUC-ROC Curve
  - Confusion Matrix

---

## 🚀 Deployment on Google Cloud
1. Model served using Flask API.
2. Docker containerization for portability.
3. Deployed on Google Cloud Run with CI/CD setup.

---

## 📂 Project Structure
ecommerce-anomaly-detection/ ├── data/ │ └── raw_data.csv ├── notebooks/ │ └── eda.ipynb ├── models/ │ └── final_model.pkl ├── src/ │ ├── data_preprocessing.py │ ├── model_training.py │ └── anomaly_detection.py ├── app/ │ └── app.py ├── Dockerfile ├── requirements.txt └── README.md
