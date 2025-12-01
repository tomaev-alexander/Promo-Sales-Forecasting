# Promo-Sales-Forecasting
This project forecasts sales for product groups during promotions. <br> The goal here is not to apply the full breadth of tools at my disposal, but rather to demonstrate general logic, ability to formulate hypotheses, and so forth. <br>
Two tables are used: products and actions. First, EDA (Exploratory Data Analysis) is performed, followed by model evaluation. The model selection is done arbitrarily, as the goal of the project is not to achieve maximum accuracy. <br>

## 📦 Libraries Used

| Category | Library | Purpose |
|----------|---------|---------|
| **Data Processing** | `pandas` | Data manipulation and analysis |
| | `numpy` | Numerical computations |
| | `PySpark` | Distributed data processing |
| | `os` | File path and OS operations |
| **Machine Learning** | `scikit-learn` | ML algorithms and utilities |
| | `DecisionTreeRegressor` | Regression tree model |
| | `GridSearchCV` | Hyperparameter tuning |
| | `OneHotEncoder` | Categorical feature encoding |
| | `TimeSeriesSplit` | Time series cross-validation |
| **Evaluation** | `sklearn.metrics` | MAE, RMSE, R² metrics |
| **Visualization** | `matplotlib` | Plotting and graphs |
| | `sklearn.tree` | Decision tree visualization |
| **Environment** | `google.colab.drive` | Google Colab integration |
