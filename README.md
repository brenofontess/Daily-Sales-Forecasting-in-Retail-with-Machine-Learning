# RetailCast

## 

## Objective: 
The RetailCast project developed a Machine Learning model to forecast daily sales for a retail chain with 70 stores across Portugal. The forecasts aim to support inventory management, optimize staff sizing, and improve promotional planning to avoid stockouts and overstock.  

## Data & Engineering: Utilizing operational data from January 2019 to October 2023, the study relied heavily on Feature Engineering. The team created temporal variables, such as 1, 7, and 14-day lags and rolling averages, while strictly preserving the chronological order during validation to prevent data leakage.  

## Model Performance: Three algorithms were compared: Linear Regression, Decision Tree, and Random Forest. The Linear Regression model achieved the best results with a Mean Absolute Percentage Error (MAPE) of 13.50%, successfully meeting the business requirement of keeping the error below 15%. It also recorded an R² of 0.9545 and a Mean Absolute Error (MAE) of 5,289 €.  

## Key Takeaways: The success of the simpler model demonstrated that high-quality temporal variables and data preparation were more decisive for predictive performance than algorithm complexity. Due to its high accuracy, interpretability, and exceptionally low training time (0.10 seconds), the Linear Regression model was recommended as the final production solution.  
