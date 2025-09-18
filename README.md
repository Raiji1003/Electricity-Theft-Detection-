# ⚡ Electricity Theft Detection  

This project focuses on **detecting electricity theft** in smart grids using advanced **ensemble learning techniques**. It leverages machine learning models to analyze consumption behavior and identify fraudulent patterns, helping utility providers minimize revenue loss.  

---

## 📌 Overview  
- Implements **multi-view learning** and **stacked ensemble models**.  
- Handles **class imbalance** using ADASYN.  
- Provides a **scalable, real-time monitoring solution** for smart grids.  

---

## 🔎 Approaches  

### 🔹 Approach 1 – Multi-View Ensemble Learning  
- 📂 Data loading and preprocessing.  
- ✂️ Splitting features into multiple views.  
- 🤖 Training models (Logistic Regression, SVM, Random Forest) on each view.  
- 🧩 Combining models using **hard/soft voting** and **stacking**.  
- 📊 Evaluating performance with **accuracy** & **confusion matrix**.  

### 🔹 Approach 2 – Stacked Ensemble Model  
- 🚀 Combined **Random Forest, XGBoost, and Logistic Regression**.  
- ⚖️ Applied **ADASYN** to handle imbalanced data.  
- 📈 Achieved **high recall** & **ROC-AUC** on imbalanced datasets.  
- ⚡ Scalable for **real-time monitoring** & anomaly detection in smart grids.  

---

## ✨ Features  
- Detects **fraudulent electricity usage patterns**.  
- Handles **imbalanced datasets** effectively.  
- Supports **real-time deployment** in smart grids.  
- Improves **model accuracy & recall** using advanced ensemble methods.  

---

## 🛠️ Tech Stack  
**Languages & Libraries:**  
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost)  

**Techniques:**  
- Multi-view learning  
- Stacking ensemble  
- ADASYN (class imbalance handling)  

---

## 📈 Results & Insights  
- ✅ Improved classification accuracy using **multi-view learning**.  
- ✅ High **recall & ROC-AUC** with stacked ensemble.  
- ✅ Real-time deployment capability for **utility providers**.  

---
