# CodeAlpha_CreditScoringModel


# Credit Scoring Model – Machine Learning  
(CodeAlpha Internship Project)

## 📌 Project Overview
This project focuses on building a **Credit Scoring Model** to predict whether an individual is **creditworthy** based on historical financial data. The model helps financial institutions make informed loan approval decisions using machine learning techniques.

This project is completed as part of the **CodeAlpha Machine Learning Internship**.

---

## 🎯 Objective
To classify individuals into:
- **Good Credit (1)**  
- **Bad Credit (0)**  

using past financial and personal attributes.

---

## 📊 Dataset
- **Dataset Name:** German Credit Dataset  
- **Source:** UCI Machine Learning Repository  
- **Records:** 1000  
- **Features:** 20 financial & personal attributes  

### Key Features Include:
- Age  
- Credit Amount  
- Duration  
- Employment Status  
- Savings Account  
- Credit History  

---

## 🧠 Machine Learning Models Used

### 1️⃣ Logistic Regression (Scaled)
- Feature scaling using `StandardScaler`
- Solved convergence issues
- Baseline linear classifier

### 2️⃣ Decision Tree Classifier (Advanced)
- Controlled depth to avoid overfitting
- Hyperparameter tuning using `GridSearchCV`
- Feature importance analysis

### 3️⃣ Random Forest Classifier (Advanced)
- Ensemble learning approach
- Hyperparameter tuning
- Best overall performance

---

## ⚙️ Techniques Implemented
- Data preprocessing & encoding
- Feature scaling (Logistic Regression)
- Model comparison
- Hyperparameter tuning
- Confusion matrix visualization
- ROC-AUC evaluation
- Feature importance analysis

---

## 📈 Model Performance Summary

| Model                | Accuracy | ROC-AUC |
|---------------------|----------|--------|
| Logistic Regression | ~74%     | ~0.75  |
| Decision Tree       | ~76%     | ~0.78  |
| Random Forest       | ~77–80%  | ~0.79+ |

✅ **Random Forest performed best** in terms of stability and ROC-AUC score.

---

## 📊 Evaluation Metrics Used
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC Score  
- Confusion Matrix  

---

## 📂 Project Structure
CodeAlpha_CreditScoringModel/
│── credit_scoring.ipynb
│── README.md
│── requirements.txt
│── screenshots/
│ ├── confusion_matrix.png
│ ├── feature_importance.png



---

## 🛠️ Technologies & Libraries
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 🚀 Conclusion
This project demonstrates how machine learning models can be effectively applied to **credit risk assessment**. Among all models, **Random Forest achieved the best performance**, making it suitable for real-world credit scoring systems.

---
