# CardioSense – Heart Disease Prediction and Interpretability
CardioSense is a machine learning project aimed at predicting heart disease outcomes and interpreting model decisions using explainable AI techniques. The project explores patterns in survival based on patient features and evaluates multiple classification algorithms to identify the most effective and interpretable model.

---

## 📊 Project Objectives

- Predict heart disease outcomes based on clinical data
- Identify key features contributing to patient survival
- Compare model performance using metrics like Accuracy, AUC-ROC
- Enhance model transparency using ELI5, LIME, and SHAP

---

## 🧠 Models Used

- Random Forest 🌲
- XGBoost ⚡
- Logistic Regression 📈
- Decision Tree 🌴

---

## 📈 Performance Summary

| Model               | Accuracy | AUC-ROC |
|--------------------|----------|---------|
| Random Forest       | 95.00%   | 0.9028  |
| XGBoost             | 93.33%   | 0.8813  |
| Logistic Regression | 88.33%   | ~0.85   |
| Decision Tree       | 88.33%   | ~0.84   |

---

## 🔍 Key Insights

- **Top Features:** `time`, `ejection_fraction`, `serum_sodium`, `age`, `serum_creatinine`
- **Gender-based Trends:**  
  - Females had higher survival in age range 40–75  
  - Males showed better survival from 40–85  
- **Smoking:** Non-smokers had concentrated survival between ages 40–70
- **Interpretability:**
  - `ELI5`: Clear feature weights for Logistic Regression and Decision Tree  
  - `LIME`: Local explanations for Random Forest and XGBoost  
  - `SHAP`: Global & local interpretation of XGBoost predictions

---

## 🧰 Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- XGBoost, RandomForestClassifier
- ELI5, LIME, SHAP
- Jupyter Notebook
