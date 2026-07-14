# 📈 Stock Price Prediction Using XGBoost

## Project Overview

This project develops a machine learning model to predict stock closing prices using the XGBoost Regressor algorithm. The workflow includes data preprocessing, feature engineering, model training, evaluation, and visualization of predictions.

The goal is to demonstrate how machine learning techniques can be applied to financial market data while following a structured data science workflow.

---

## Dataset

The dataset contains historical stock trading information with the following features:

- Date
- Stock Symbol
- Opening Price
- Closing Price
- Trading Volume
- Sector

**Target Variable**

- Closing Price

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Encoding Categorical Variables
6. Train-Test Split
7. XGBoost Model Training
8. Model Evaluation
9. Feature Importance Analysis
10. Model Saving

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Joblib

---

## Machine Learning Model

- XGBoost Regressor

### Hyperparameters

- n_estimators = 200
- learning_rate = 0.05
- max_depth = 5
- random_state = 42

---

## Evaluation Metrics

The model is evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Results

Example evaluation metrics:

| Metric | Value |
|---------|-------|
| MAE | XX |
| RMSE | XX |
| R² Score | XX |

*(Replace the values with your model's actual results.)*

---

## Visualizations

- Actual vs Predicted Closing Prices
- Feature Importance
- Correlation Heatmap

---

## Future Improvements

- Incorporate High and Low prices.
- Add technical indicators (Moving Average, RSI, MACD, Bollinger Bands).
- Perform hyperparameter tuning.
- Use TimeSeriesSplit for model validation.
- Compare XGBoost with Random Forest, LightGBM, and LSTM.

---

## Repository Structure

```text
data/
images/
models/
notebooks/
README.md
requirements.txt
```

---

## Author

**Elijah Adeniji**

Industrial Chemistry Graduate | Data Scientist | Machine Learning Enthusiast

GitHub: https://github.com/adeniji elijah

LinkedIn: https://linkedin.com/in/adeniji elijah