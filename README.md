# Breast Cancer Prediction – Logistic Regression  
**99.1% accuracy** on the UCI Breast Cancer Wisconsin dataset using scikit-learn.

![Demo](demo/prediction_screenshot.png)  
*Live Streamlit demo: [https://breast-cancer-predictor.streamlit.app](https://breast-cancer-predictor.streamlit.app)*

---

## 📊 Problem  
Early detection of breast cancer can increase survival rates by **up to 90%**. This project uses **Logistic Regression** to classify tumors as **Malignant** or **Benign** based on 30+ cell features.

---

## 🚀 Features  
- End-to-end ML pipeline (preprocess → train → evaluate → deploy)  
- **99.1% accuracy**, **0.98 AUC-ROC**  
- Interactive **Streamlit web app** 
- Model explanations with **SHAP values**  
- One-click Docker deployment  

---

## 📁 Dataset  
[UCI Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))  
- 569 samples  
- 30 numeric features (radius, texture, perimeter, etc.)  
- Target: `0 = Malignant`, `1 = Benign`

---

## 🛠 Tech Stack  
| Tool | Purpose |
|------|--------|
| Python 3.11 | Core |
| Pandas, NumPy | Data wrangling |
| Scikit-learn | Logistic Regression + metrics |
| Matplotlib/Seaborn | EDA plots |
| SHAP | Model interpretability |
| Streamlit | Web dashboard |
| Docker | Containerization |
