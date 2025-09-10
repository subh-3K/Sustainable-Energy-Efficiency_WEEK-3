# 🏠 Building Energy Efficiency Prediction

## 📌 Project Overview
This project predicts the **Heating Load** and **Cooling Load** of buildings based on their architectural features.  
By using Machine Learning models, we can understand how building characteristics (e.g., surface area, glazing, orientation) impact energy demand.  

---

## 🚩 Problem Statement
Buildings consume a large portion of global energy.  
Predicting heating and cooling loads helps in **designing energy-efficient buildings** and **reducing environmental impact**.  

---

## 🎯 Learning Objectives
- Understand how building features affect energy demand.  
- Apply **Machine Learning** to predict Heating & Cooling Loads.  
- Build an **end-to-end pipeline**: data preprocessing → training → evaluation → deployment.  

---

## 🛠️ Tools & Technologies
- **Python 3.12**  
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn, joblib  
- **Framework**: Streamlit (for web deployment)  
- **Dataset**: UCI Energy Efficiency Dataset  

---

## 🔬 Methodology
1. **Data Preprocessing**  
   - Handle numeric & categorical features  
   - Apply scaling and one-hot encoding  

2. **Model Training**  
   - Separate models for Heating Load and Cooling Load  
   - Used **Linear Regression / Random Forest**  

3. **Evaluation**  
   - Metrics: MAE, RMSE, R²  

4. **Deployment**  
   - Saved trained models with `joblib`  
   - Built Streamlit app for user-friendly predictions  

---

## ✅ Solution
- Users enter building parameters:  
  - Relative Compactness  
  - Surface Area  
  - Wall Area  
  - Roof Area  
  - Overall Height  
  - Glazing Area  
  - Orientation  
  - Glazing Area Distribution  
- Model predicts **Heating Load** and **Cooling Load** instantly.  

---

## 📊 Output
Example prediction:  
Heating Load Prediction: 25.3
Cooling Load Prediction: 28.5
