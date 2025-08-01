# Enhancing the Reliability of Concrete Infrastructure through Explainable Machine Learning Insights into Rebar Corrosion

## Abstract

Rebar corrosion in reinforced concrete poses a critical threat to structural integrity and public safety, often causing costly and disruptive inspections. This study introduces an innovative predictive framework using three explainable machine learning models: CatBoost, Lasso regression, and a feature-selected variant of CatBoost. To enhance model reliability and reduce multicollinearity, it utilizes the minimum-redundancy
6maximum-relevance (mRMR) feature selection prior to model development. Model performance, assessed using standard regression metrics, yields R2 values of 0.67 (Lasso model), 0.96 (CatBoost with mRMR-features), and 0.98 (CatBoost with all features). The Jackknife+ method, applied to CatBoost model, generates prediction intervals with 93% coverage, enabling effective uncertainty quantification. Thorough feature importance analysis highlights that electrochemical indicators and mortar characteristics account for over 70% of CatBoost’s predictive capacity. While CatBoost excels in accuracy and interpretability, the Lasso model offers a straightforward and transparent formulation with built-in feature selection via its regularization parameter (alpha). This integrated modeling approach empowers engineers to optimize maintenance schedules, select durable materials, and implement advanced monitoring systems, ultimately reducing corrosion-induced failures and extending the reliability and service life of reinforced concrete infrastructure.

## Contents
- **Jupyter Notebook**: All source code used to generate the results is available in Jupyter Notebook file.
- **Dataset**: carbonation and chloride-induced steel corrosion in cementitious mortars
- **Dataset's Paper**: https://doi.org/10.1016/j.dib.2024.110595
- **Paper Link**: Will be available after acceptance
- **Dependencies**: These dependencies are listed in the `requirements.txt` file. To install them, run: `pip install -r requirements.txt`

## Authors:
- Hassan Mesghali
- Behnam Akhlaghi
- Mir Amir Mohammad Reshadi
- Javad Mohammadpour
- Fatemeh Salehi
- Rouzbeh Abbassi
