

---

# 🚨 Financial Transaction Fraud Detection

### **End-to-End Machine Learning Pipeline with EDA, Feature Engineering & Modeling**

This project builds a complete **fraud detection system** using a **synthetic dataset of 10,000 financial transactions**. The goal is to analyze transactional behavior, identify fraud patterns, engineer meaningful features, and train machine learning models capable of detecting fraudulent activity.

The dataset is 100% synthetic, making it safe for research and experimentation without exposing sensitive information.

---

## 📊 **Project Overview**

This notebook covers the **entire ML workflow**, including:

* 🔍 Exploratory Data Analysis (EDA)
* 📈 Visualization of transaction and fraud patterns
* 🧹 Data preprocessing & cleaning
* 🏗 Feature engineering
* ⚖ Handling imbalanced data (SMOTE)
* 🤖 Training multiple ML models
* 🧪 Model evaluation (Precision, Recall, F1, ROC-AUC)
* 🧠 Feature importance and fraud insights
* 📌 Final conclusions and next steps

---

## 🧾 **Dataset Description**

The dataset contains **10,000 synthetic financial transactions** designed to simulate realistic fraud behaviors.

### **📌 Key Columns**

* `transaction_id` — Unique transaction reference
* `user_id` — User performing the transaction
* `amount` — Transaction amount
* `transaction_type` — POS, Online, ATM, QR
* `merchant_category` — Merchant type
* `country` — Country of transaction
* `hour` — Time of day (0–23)
* `device_risk_score` — Device risk indicator
* `ip_risk_score` — IP address risk indicator
* `is_fraud` — Fraud label (0 = Legit, 1 = Fraud)

### **📌 Simulated Fraud Behaviors**

* High-value transactions
* Unusual foreign locations
* Night-time activity
* Rapid multiple transactions
* New/untrusted devices
* High-risk IP addresses

---

## 🛠 **Technologies Used**

| Category           | Tools                               |
| ------------------ | ----------------------------------- |
| Programming        | Python                              |
| Data Analysis      | Pandas, NumPy                       |
| Visualization      | Matplotlib, Seaborn                 |
| Machine Learning   | Scikit-Learn, XGBoost               |
| Imbalance Handling | SMOTE (Imblearn)                    |
| Model Evaluation   | ROC-AUC, F1-Score, Confusion Matrix |

---

## 📚 **Notebook Contents**

### **1. Import Libraries**

Set up all ML and data analysis tools.

### **2. Load & Inspect Data**

Shape, type, structure, missing values, duplicates.

### **3. Exploratory Data Analysis (EDA)**

* Univariate plots
* Categorical feature analysis
* Fraud vs feature comparison
* Risk score behavior

### **4. Bivariate Analysis**

* Fraud vs Amount
* Fraud vs Hour
* Fraud across Transaction Types
* Country-wise fraud rate

### **5. Correlation Analysis**

* Heatmap
* Numeric associations

### **6. Feature Engineering**

* Time ranges
* Amount bins
* Encodings
* Risk-based transformations

### **7. Data Preprocessing**

* Label encoding
* Scaling
* Train-test split

### **8. Fix Imbalanced Dataset**

Apply **SMOTE** for generating synthetic fraud samples.

### **9. Train ML Models**

Models used:

* Logistic Regression
* Random Forest
* Decision Tree
* KNN
* XGBoost

### **10. Model Evaluation**

* Classification Report
* Confusion Matrix
* ROC-AUC Curve
* Feature Importance

### **11. Final Fraud Insights**

Key behavioral findings and model performance summary.

---

## 🧪 **Results Summary**

* Fraud shows strong correlation with **amount**, **risk scores**, and **time of day**.
* **XGBoost** performed best with the highest ROC-AUC score.
* SMOTE significantly improved fraud recall.
* Night-time and foreign transactions had higher fraud probability.

---

## 📌 **Project Goals**

✔ Build a complete fraud detection ML pipeline
✔ Identify behaviors that indicate suspicious activity
✔ Compare multiple models and find the best performer
✔ Provide a ready-to-run notebook for developers & researchers

---

## 🚀 **Future Improvements**

* Add deep learning models (LSTM for sequence transactions)
* Use anomaly detection (Isolation Forest, Autoencoders)
* Build real-time fraud scoring API
* Deploy using Streamlit or FastAPI

---

## 🤝 **Contributions**

Contributions are welcome!
If you'd like to improve this project, create a pull request or open an issue.

---

## ⭐ **Support**

If you found this project helpful:
**Give this repository a star ⭐ on GitHub!**

---


