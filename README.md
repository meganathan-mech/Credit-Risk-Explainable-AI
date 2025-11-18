# 💳 Credit Risk Prediction Using Explainable AI

This project predicts whether a loan applicant will default, helping banks reduce losses and make safe lending decisions.

---

## 🔍 Objective
Predict loan default risk using:
- XGBoost Classifier
- SHAP (Global Explainability)
- LIME (Local Explainability)

---

## 📂 Dataset
- File used: `application_train.csv`
- Source: Home Credit Default Risk
- Target column:
  - `1` → Default
  - `0` → No Default

---

## ⚙️ Project Steps

1️⃣ Data Preprocessing  
2️⃣ Model Training (XGBoost)  
3️⃣ Model Evaluation  
4️⃣ SHAP Feature Importance  
5️⃣ LIME Individual Customer Explanations  

---

## 📊 Results

| Metric | Score |
|--------|------|
| ROC-AUC | **0.7548** |
| PR-AUC | **0.2374** |

---

## 🧠 Explainable AI Insights

### 🟥 SHAP
- Shows top risk-driving features globally

### 🟦 LIME
- Explains individual loan decisions

---

## 📈 Business Impact
✔ Better decision support for loan approval  
✔ Reduced financial risk for banks  
✔ Faster approval for good customers  

---

## 🛠️ Technologies Used
- Python
- Scikit-learn
- XGBoost
- SHAP
- LIME
- Google Colab

---

## 📌 Files in This Repository
| File | Description |
|------|------------|
| `Project.ipynb` | Full code and results |

---

## 👤 Author
Your Name — Data Science Trainee  
