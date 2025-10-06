# 🧬 COVID-19 Vaccination Data Analysis & Predictive Modeling

This project analyzes U.S. COVID-19 vaccination trends and builds predictive models to estimate future vaccination counts.  
It combines **data engineering**, **exploratory data analysis (EDA)**, and **machine learning** to uncover insights and forecast national vaccination progress.

---

### 🚀 Project Overview
- **Objective:** Analyze vaccination distribution patterns across U.S. states and forecast total vaccinations using machine learning.  
- **Tech Stack:** Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, H2O AutoML, SHAP, LIME  
- **Core Techniques:** Regression modeling, feature engineering, regularization, model interpretability, AutoML optimization  

---

### 🗂️ Data Preprocessing
- **Data Source:** Public COVID-19 vaccination dataset (CDC / Our World in Data).  
- **Data Cleaning:** Handled missing values with interpolation and zero-filling for continuous time-series consistency.  
- **Feature Engineering:** Derived vaccination rate per 100 people, daily change, and population-adjusted ratios.  
- **Data Validation:** Ensured data completeness and outlier removal using Pandas Profiling and correlation analysis.  

---

### 🤖 Machine Learning Workflow
1. **Exploratory Analysis:** Visualized vaccination trends and state-level disparities using Seaborn and Matplotlib.  
2. **Model Development:** Trained multiple supervised models:  
   - Linear Regression (baseline)  
   - Random Forest Regressor (ensemble)  
   - MLP Regressor (neural-network-based)  
3. **Regularization:** Applied **Ridge**, **Lasso**, and **Elastic Net** to reduce overfitting and improve model generalization.  
4. **AutoML Integration:** Leveraged **H2O AutoML** to automate model selection and hyperparameter tuning — **Gradient Boosting Machine (GBM)** delivered the most stable performance.  
5. **Evaluation Metrics:** Compared models using RMSE, MAE, and R² scores for accuracy and consistency.  

---

### 🧩 Model Interpretability
To enhance transparency and explainability:  
- **SHAP (SHapley Additive Explanations):** Identified key drivers behind vaccination rate predictions.  
- **LIME (Local Interpretable Model-agnostic Explanations):** Visualized local feature contributions for individual predictions.  
- **Partial Dependence Plots (PDP):** Illustrated marginal feature effects and feature-interaction dynamics.  

---

### 📊 Key Insights
- Population density, healthcare access, and prior infection rates were top predictors influencing vaccination rates.  
- Regularization improved model generalization across multiple data slices.  
- AutoML-optimized **Gradient Boosting** achieved the best trade-off between performance and interpretability.  
