# Probabilistic assessment of rebar corrosion using explainable machine learning

## Abstract

Rebar corrosion in reinforced concrete poses a significant threat to infrastructure performance and safety. Traditional inspection methods are often disruptive and costly. This study develops and compares explainable CatBoost and Lasso machine learning models for rebar corrosion prediction, utilizing a comprehensive dataset. Model development involved full feature combinations and filtered features, identified through the minimum-redundancy maximum-relevance (mRMR) method, to address the issue of multi-collinearity and enable more accurate and reliable predictions. All modeling scenarios were evaluated using five performance metrics, achieving high accuracy with only a negligible decrease in performance when using the mRMR-filtered feature subset. A robust Jackknife+ method was applied to the CatBoost model with the mRMR subset to estimate prediction intervals, providing a range of possible corrosion values through uncertainty quantification. The CatBoost model's interpretation revealed the relative importance and interactive influence of input features, highlighting electrochemical indicators and mortar characteristics as key contributors to rebar corrosion predictions. These factors collectively accounted for over 70% of CatBoost's predictive capacity. While CatBoost demonstrated higher predictive accuracy, the Lasso model offers a simple, interpretable formulation of the rebar corrosion process, enabling engineers to easily understand and apply the results. The Lasso model's ability to perform feature selection through its regularization parameter (alpha) provides an additional advantage. By integrating these modeling approaches, engineers and infrastructure managers can optimize maintenance schedules, inform material selection, enhance structural durability assessments, and leverage advanced monitoring systems. This holistic framework ultimately reduces corrosion-induced failures, ensures public safety, and extends the service life of reinforced concrete structures.


## Contents
- **Jupyter Notebook**: All source code used to generate the results is available in Jupyter Notebook file.
- **Dataset**: Dataset on carbonation and chloride-induced steel corrosion in cementitious mortars
- **Dataset Paper**: https://doi.org/10.1016/j.dib.2024.110595
- **Paper Link**: Will be available after acceptance

## Dependencies

```plaintext
pandas==2.2.2
numpy==1.26.4 
matplotlib==3.10.0
seaborn==0.13.2
scienceplots==2.1.1
scikit-learn==1.5.2
optuna==4.2.0
scipy==1.13.1
tqdm==4.67.1
puncc==0.8.0
mapie==0.9.2
scikit-lego==0.9.4
catboost==1.2.7
shapiq==1.2.0
```

## Authors:
- Hassan Mesghali
- Behnam Akhlaghi
- Mir Amir Mohammad Reshadi
- Javad Mohammadpour
- Fatemeh Salehi
- Rouzbeh Abbassi
