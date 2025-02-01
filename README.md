# ML-Projects

This repository contains various machine learning projects aimed at solving different data challenges and improving model performance through various techniques.

## Projects

### 2. Heart Disease Prediction – Minimizing Overfitting  

This project focuses on heart disease prediction while implementing techniques to minimize overfitting.

#### Steps Taken:
- **Data Splitting:** Manually split the dataset to prevent data leakage.
- **Multicollinearity Check:** Performed **Variance Inflation Factor (VIF)** analysis to ensure feature independence.
- **Categorical Data Handling:** Used **Label Encoding**, as it was the best approach for low-cardinality categorical features.
- **Feature Scaling:** Scaled the data before **Principal Component Analysis (PCA)** to ensure fair dimensionality reduction.
- **Dimensionality Reduction:** Applied PCA based on **Proportion of Variance Explained (PVE)** and cumulative variance for optimal feature selection.
- **Feature Importance:** Analyzed **loadings vectors** to understand how each feature contributes to the principal components.
- **Overfitting Prevention:** Utilized the **Ridge Classifier** with varying **alpha** values to reduce overfitting.

#### 🔍 Key Takeaways
These steps helped balance model performance and complexity, ensuring a more reliable heart disease prediction model.
