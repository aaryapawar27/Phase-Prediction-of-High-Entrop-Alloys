## ⚙️ Phase Prediction of High Entropy Alloys | Machine Learning Project

## 🧠 Overview
This project focuses on predicting the **phase formation in High Entropy Alloys (HEAs)** using machine learning.  
High Entropy Alloys are multi-component metallic systems with exceptional mechanical and thermal properties.  
Understanding their phase behavior (FCC, BCC, or Mixed) is crucial for designing new materials with tailored performance.  
This work aims to build a predictive model that determines alloy phases from elemental and thermodynamic features — minimizing the need for costly and time-consuming experiments.

---

## 🎯 Objectives
- Predict the **phase type** of HEAs using compositional and thermodynamic descriptors.  
- Identify the key parameters influencing phase stability and transformation.  
- Enable a **data-driven approach** for alloy design and discovery.

---

## 📊 Dataset & Features
- Dataset of **1400+ HEA samples** compiled from published research papers and materials databases.  
- Features include:
  - Atomic size difference (δ)  
  - Electronegativity difference (Δχ)  
  - Valence electron concentration (VEC)  
  - Mixing enthalpy (ΔHₘᵢₓ)  
  - Mixing entropy (ΔSₘᵢₓ)  
- Target variable: **Phase type** → FCC / BCC / Mixed  

---

## 🧩 Methodology
1. **Data Preprocessing:** Cleaned and standardized data, handled missing values, and encoded categorical variables.  
2. **Exploratory Data Analysis (EDA):** Visualized correlations and phase distributions to identify key patterns.  
3. **Feature Engineering:** Derived features representing atomic interactions and thermodynamic stability.  
4. **Model Building:** Implemented **Random Forest** and **XGBoost** classifiers.  
5. **Evaluation:** Achieved an **F1-score of 0.83** using cross-validation and hyperparameter tuning.

---

## 🔍 Key Insights
- **VEC** and **atomic size difference** were found to be the most influential features for phase formation.  
- The model provides a **computationally efficient alternative** to experimental phase identification.

---

## 🧰 Tech Stack
**Languages:** Python  
**Libraries:** pandas, NumPy, scikit-learn, Matplotlib, Seaborn, XGBoost  

---

## 🚀 Impact & Future Work
This project showcases how **machine learning accelerates materials discovery** by predicting phase behavior in complex alloy systems.  
Future improvements include:
- Integrating **thermodynamic simulation tools (e.g., Thermo-Calc)**  
- Deploying a **web-based phase prediction dashboard** for materials researchers.

---

## 📂 Repository Structure

