# RetailCast: Daily Sales Forecasting

**Objective:** Develop a Machine Learning model to forecast daily sales for a retail chain of 70 stores across Portugal, aiming to optimize inventory management, staff sizing, and promotional planning while preventing stockouts and overstock.

### 📊 Data & Feature Engineering
* **Dataset:** Operational retail data (January 2019 to October 2023).
* **Engineering:** Extensive creation of temporal variables, including 1, 7, and 14-day lags, and rolling averages.
* **Validation:** Strict walk-forward validation to preserve chronological order and prevent data leakage.

### 🤖 Model Performance
* **Models Evaluated:** Linear Regression, Decision Tree, Random Forest.
* **Winning Model:** Linear Regression.
* **Key Metrics:**
  * **MAPE:** 13.50% *(Successfully met business requirement of < 15%)*
  * **R²:** 0.9545
  * **MAE:** 5,289 €

### 💡 Key Takeaways
* **Data over Algorithm:** High-quality temporal features and robust data preparation proved more decisive for predictive performance than algorithm complexity.
* **Production Decision:** Linear Regression was selected as the final solution due to its optimal balance of high accuracy, business interpretability, and exceptionally low computational cost (0.10 seconds training time).
