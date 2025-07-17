# CarPricePrediction
Car Price Prediction – Short Report
1. Exploratory Data Analysis (EDA)
The dataset contains 4276 car records with features such as year, km_driven, fuel, seller_type, transmission, etc.

Majority of cars are from recent years (2012 onward).

Petrol and Diesel dominate as fuel types.

Selling price tends to drop as km_driven increases.

2. Model Results
A Linear Regression model was trained using encoded features.

Model Evaluation:

R² Score: ~0.40 (moderate prediction strength)

MAE, MSE, RMSE indicate average errors

Model performance is decent for basic estimation but lacks precision.

3. Conclusion
The model provides a rough price estimate.

Improvement possible via:

More powerful models (e.g., Random Forest, XGBoost)

Better feature engineering

More real-world testing
