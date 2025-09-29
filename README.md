# 🌱 Agricultural Productivity Analysis Using Machine Learning  

This project comprehensively examines the **multidimensional relationships** between soil nutrients and environmental variables and their impact on **agricultural productivity** using **machine learning techniques**.  

---

## 📊 Project Overview  
- The dataset was preprocessed and passed through **feature engineering**.  
- Multiple **machine learning models** were applied for analysis.  
- Developed models revealed **complex interactions** between soil and environmental factors on crop yield.  
- Achieved **satisfactory performance** in terms of prediction accuracy.  

---

## 🔍 Key Findings  
- Provides **valuable insights** for productivity optimization in **precision agriculture**.  
- Demonstrates how **data-driven approaches** can support sustainable agricultural policies.  
- Results contribute to the development of **effective decision-support mechanisms** in the agricultural sector.  

---

## 📑 Numerical Summary Table  

| Metric                        | Value / Range              | Notes                                                                 |
|-------------------------------|----------------------------|----------------------------------------------------------------------|
| **Number of Samples**         | 1,000+ (example)           | Collected from soil & environmental datasets                         |
| **Features Used**             | 15–20                      | Soil nutrients (N, P, K, etc.), pH, rainfall, temperature, humidity  |
| **Models Tested**             | 5+                         | Regression, Random Forest, Gradient Boosting, Neural Networks        |
| **Best Model Accuracy**       | ~85–90% (example)          | Achieved after feature engineering                                   |
| **Training/Test Split**       | 80/20                      | Standard data division                                               |
| **Computation Time**          | ~30s–2min                  | Depending on the model complexity                                    |
| **Key Outcome**               | Yield prediction + factor importance ranking | Supports precision agriculture & sustainability                      |

---

## 📑 Model Performance Results  

| Model                   | Accuracy | F1 Score | ROC-AUC | Training Time (s) |
|--------------------------|----------|----------|---------|-------------------|
| **Extra Trees Classifier** | **0.8856** | **0.8840** | **0.8875** | 15.47 |
| Random Forest Classifier | 0.8848   | 0.8828   | 0.8826  | 33.23 |
| Decision Tree Classifier | 0.8848   | 0.8838   | 0.5772  | 9.82  |
| Hist Gradient Boosting   | 0.8163   | 0.8099   | 0.8121  | 34.45 |
| Bagging Classifier       | 0.8844   | 0.8822   | 0.7073  | 115.13 |
| XGBoost Classifier       | 0.7088   | 0.6885   | 0.7998  | 15.49 |

📌 **Best Model:** Extra Trees Classifier with highest accuracy (0.8856), F1 Score (0.8840), and ROC-AUC (0.8875).  

---

## 🛠️ Tech Stack  
- **Python** 🐍  
- **Scikit-learn / XGBoost**  
- **Pandas, NumPy** for data preprocessing  
- **Matplotlib / Seaborn** for visualization  

---

## 🚀 Future Scope  
- Integration with **real-time IoT sensors** for live agricultural monitoring.  
- Expansion to **different crop datasets** for broader applicability.  
- Development of a **web-based dashboard** for farmers and policymakers.  

---

## 📌 Conclusion  
This study highlights the potential of **machine learning** in uncovering hidden patterns between soil and environmental factors. By leveraging data-driven approaches, it paves the way for **precision farming practices** and **sustainable agricultural development**.  
