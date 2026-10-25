# Airbnb Price Prediction – Brisbane 🏠

Group Kaggle competition project for BUSA3020 (Advanced Analytics) at Macquarie University.
Goal: predict the nightly price (AUD) of Airbnb listings in Brisbane.

## My role
Team Leader and owner of the Exploratory Data Analysis (EDA) task.

## Approach
- Cleaned and explored 3,735 listings with 65 variables (missing values, skewed prices, outliers)
- Selected and engineered 20+ features (location, room type, capacity, host and review data)
- Trained and tuned Ridge, Random Forest and XGBoost models using 5-fold cross-validation
- Tested ensemble methods (Voting and Stacking)

## Results
| Model | CV MAPE |
|---|---|
| Ridge | 27.3% |
| Random Forest | 23.1% |
| XGBoost (regularised) | **21.3%** |

Final Kaggle score: **22.0% MAPE**

## Tools
Python, pandas, NumPy, Matplotlib, scikit-learn, XGBoost

## Team
Evelyn (Dan Thanh) Vu, Thi My Duyen Vo, Thao Trinh Than
