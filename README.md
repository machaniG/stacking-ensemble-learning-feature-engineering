# Hunting for Missing Values, Feature Engineering, and Ensemble Learning

This project presents proof of concept **stacking models using a meta-learner** coupled with advanced **feature engineering** including **polynomial features** results in more accurate predictions compared to individual models.

---

## Project Highlights

- Robust data cleaning, hunting for missing values, and preprocessing
- Basic EDA
- Advanced feature engineering including polynomial features and interaction terms
- Stacking multiple base models (e.g., RidgeCV, RandomForest, LightGBM, XGBoost, CatBoost, etc.)
- Hyperparameter tuning using `GridSearchCV`
- Feature selection


---

## Tech Stack

- **Languages**: Python 3.9+
- **Libraries**: pandas, numpy, scikit-learn, xgboost, lightgbm, catboost, seaborn, matplotlib
- **Modeling**: StackingRegressor, RidgeCV, RandomForest, BaggingRegressor, LightGBM, XGBoost, CatBoost
- **Feature Engineering**: Polynomial features, interaction terms, one-hot encoding, standardization
- **Tuning**: GridSearchCV

