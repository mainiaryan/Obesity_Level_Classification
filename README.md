# 🧠 Obesity Level Prediction using Machine Learning

## 📌 Overview
This project focuses on predicting obesity levels using supervised machine learning techniques based on individuals' lifestyle habits and physical attributes. It is a multi-class classification problem with seven obesity categories.

---

## 🎯 Objectives
- Build accurate models for obesity level classification  
- Compare multiple ML algorithms  
- Analyze feature importance and optimize model complexity  

---

## 📊 Dataset
- Source: Kaggle – Obesity Levels Dataset  
- Records: 2,111 samples  
- Features: 17 attributes  
- Target: 7 obesity classes (Insufficient Weight → Obesity Type III)  
- Data is clean, balanced, and contains no missing values  

---

## ⚙️ Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly  
- Scikit-learn  
- XGBoost  

---

## 🔄 Workflow
1. Data Loading & Exploration (EDA)  
2. Data Preprocessing (Encoding + Scaling)  
3. Train-Test Split (80:20, stratified)  
4. Model Training  
5. Evaluation (Accuracy, Confusion Matrix, Classification Report)  
6. Feature Selection Analysis  

---

## 🤖 Models Used
- Support Vector Machine (SVM)  
- Random Forest  
- XGBoost  
- Blended Ensemble (SVM + RF + XGB)  

---

## 📈 Results
| Model            | Accuracy |
|------------------|----------|
| SVM              | 95.74%   |
| Random Forest    | 95.74%   |
| XGBoost          | **96.22%** |
| Ensemble         | 95.98%   |

---

## 🔍 Key Insights
- XGBoost performed best due to its boosting capability  
- Most errors occurred between similar classes  
- Feature importance revealed strong impact of weight, diet, and lifestyle  

---

## ⚖️ Feature Selection Insight
- Top 8 features achieved ~95% accuracy  
- Adding more features gave minimal improvement  
- Demonstrates trade-off between performance and complexity  

---

## 🚀 Future Improvements
- Apply cross-validation for robustness  
- Use SHAP for model explainability  
- Deploy model using Streamlit or web app  

---

## 📌 Conclusion
Machine learning models can effectively predict obesity levels. Optimizing feature selection helps maintain high accuracy while reducing model complexity, making the solution efficient and practical.

---

## 👤 Author
**Aryan Maini**
