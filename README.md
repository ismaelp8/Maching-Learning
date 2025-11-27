# Maching-Learning
This repository contains a collection of Maching Learning projects. It includes exploratory analyses, predictive modeling, dimensionality reduction and model evaluation using real-world datasets.

Currently included projects:

- **BarcelonaMotorIBEX** – Predictive modeling of NO₂ pollution levels in Barcelona.
- **Vacaciones** – Classification of user ratings using linear and Bayesian models.

---

## 📂 Repository Structure


Each folder includes the main notebook, generated figures, and supporting resources required to reproduce the analysis.

---

## 🔷 Projects Overview

### **BarcelonaMotorIBEX**
A predictive study analyzing daily **NO₂ levels in l’Eixample (Barcelona)** using open data from the city (2022–2024). The dataset includes:

- Vehicle registrations  
- Inter-city mobility counts  
- Electricity prices  
- Traffic volume  
- Meteorological variables (temperature, wind, precipitation) from multiple observatories  

The project includes:

- Train/Test split (60/40) and exploratory data analysis  
- Data transformation and feature preprocessing  
- Dimensionality reduction (PCA or similar)  
- Models: **Linear Regression, Ridge Regression, LASSO**  
- Prediction vs. ground truth visualizations + residual analysis  
- Identification of redundant meteorological stations  
- Statistical significance analysis using **OLS (statsmodels)**  
- Feature selection based on significance  
- Expansion with **PolynomialFeatures (degree 2, interaction_only=True)**  
- Comparison of improved models (Linear + LASSO)

---

### **Vacaciones**
A classification project involving user ratings from 0 to 4. Key components:

- Exploratory analysis + correlation study  
- Identification of slight class imbalance  
- Applied models:  
  - **Gaussian Naive Bayes** (with and without Gaussianization)  
  - **Linear Discriminant Analysis (LDA)**  
  - **Logistic Regression** with hyperparameter tuning  
- Cross-validation + metrics: Accuracy, F1-score, ROC–AUC  
- Confusion matrices and ROC curves  
- Use of `class_weight='balanced'` to improve recall for the minority class  
- Interpretation of coefficients from the best model  

---

## 🛠️ Technologies Used

- Python 3  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-Learn  
- Statsmodels  
- apafib (Barcelona open data loader)

---
