# Medical Insurance Charges Predictor

## Overview

This project predicts individual medical insurance charges using a trained machine learning model wrapped in a FastAPI web service. The model was built on the [Medical Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance) and predicts charges based on demographic and lifestyle features.

## Features

- Cleans and preprocesses raw input data (encoding categorical variables, handling outliers)
- Trains and compares several regression algorithms (Linear Regression, SVR, Random Forest, Gradient Boosting, XGBoost)
- Hyperparameter optimization with GridSearchCV
- Feature selection based on importance
- Model serialization (pickle)
- REST API endpoint for real-time predictions using FastAPI

## Dataset

- `Columns:` age, sex, bmi, children, smoker, region, charges
- No missing values; basic descriptive and statistical analysis included

---DEMO
<img width="823" height="463" alt="{64D2F29C-B3E6-4167-AAED-261174BE039E}" src="https://github.com/user-attachments/assets/02f360a4-1166-4fc4-9c71-69a0fbf2fe7a" />


---

## License

This project is licensed under the MIT License.

## Acknowledgments

- Model built with: Pandas, scikit-learn, XGBoost, seaborn, matplotlib, FastAPI
- Dataset source: [Kaggle - Medical Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

---

For any questions or contributions, please open an issue or pull request.


