# Marketing Mix Modeling

Sales of Brand X is given for 3238 stores. Also price of 5 competitors of Brand X (in those stores) is given.

In addition to Sales, the following information are also given:
- Price: Avg price of Brand X in that store
- Feature: Whether value-added variant of Brand X is present in the store (1) or not (0)
- Display: Whether any store level promo of  Brand X is present in the store (1) or not (0)
- Price-Competitors: Prices of 5 competition brands in the store have been given also

Working
-

- Perform OLS Regression using all features.
- Check significance of features (by P-value) and drop insignifant ones and do OLS again.
- Check adjusted R score, if it doesn't improve, try feature engineering.
- Check interaction effect between variables and make new features.
- Check adjusted R score and mean absolute error.
- Perform model building using DecisionTreeRegressor, RandomForestRegressor, KNeighborsRegressor.
- Also perform hyperparameter tuning and apply crossvalidation for best result.
