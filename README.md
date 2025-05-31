
## 📘 Dataset

- **Source**: [Kaggle – Diamonds Dataset](https://www.kaggle.com/datasets/shivam2503/diamonds)
- **Records**: 53,940 diamonds
- **Features**: Includes cut, color, clarity, carat, depth, table, x, y, z, price, and derived market demand.

## 📄 Papers Referenced

1. **Sharma et al. (2021)**  
   *Comparative Analysis of Supervised Models for Diamond Price Prediction*

2. **Kapil Amadavadi et al. (2024)**  
   *Diamond Price Prediction using Machine Learning Techniques*

3. **Fitriani et al. (2022)**  
   *LASSO and k-NN Algorithm Analysis Based on Feature Selection for Diamond Price Prediction*

## 🔍 What This Project Does

- Implements and compares various regression models as discussed in the three referenced papers, including:
  - Linear Regression, Ridge, Lasso, Decision Tree, Random Forest, Extra Trees, Gradient Boosting, KNN, MLP, and XGBoost.
- Reproduces key preprocessing steps:
  - Label encoding, standardization, correlation analysis (as in Sharma and Amadavadi et al.)
  - Feature selection using SelectKBest with f_regression (as emphasized by Fitriani et al.)
- Evaluates the effect of full-feature vs. reduced-feature models on predictive performance.
- Benchmarks all models using RMSE and R² metrics, consistent with the methodologies across all three studies.


## 🧪 Goal

To evaluate how different supervised learning models perform in predicting diamond prices, and how feature selection and preprocessing strategies influence those results.

---

