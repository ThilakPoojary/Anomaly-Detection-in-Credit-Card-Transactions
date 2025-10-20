# Credit Card Fraud Detection using Anomaly Detection

## Project Overview
This project implements an **anomaly detection system** to identify potential fraudulent credit card transactions. Using the **Isolation Forest** algorithm, it detects unusual patterns in transaction data without requiring labeled fraud examples. The system is deployed as a **Flask API** for easy integration and real-time predictions.

---

## Features
- **Data Preprocessing:** Handles missing values and scales features using `SimpleImputer` and `StandardScaler`.
- **Anomaly Detection:** Detects fraudulent transactions using Isolation Forest.
- **Flask API:** Real-time prediction endpoint (`/predict`) for batch or single transactions.
- **PCA Visualization (Optional):** Visualizes anomalies in 2D using PCA.
- **Batch Prediction:** Accepts multiple transactions in JSON format for bulk analysis.

---

## Technology Stack
- Python 3.x  
- Pandas & NumPy  
- Scikit-learn (Isolation Forest, Pipeline, Preprocessing)  
- Flask (API deployment)  
- Joblib (model serialization)  
- Matplotlib (optional visualization)

---

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/CreditCardFraudDetection.git
cd "CreditCardFraudDetection"
