Predicting Population Growth in U.S. Cities: A Regression-Based Approach

This project explores urban population growth in U.S. cities using supervised machine learning techniques applied to American Community Survey (ACS) data from 2010–2019. The study focuses on leveraging socioeconomic, housing, and demographic features to predict population growth within federally defined city boundaries. Linear Regression, Random Forest, and XGBoost models were implemented, with extensive feature engineering (e.g., lagged variables, one-hot encoding, rolling averages) to maintain the temporal integrity of the dataset.

Linear Regression consistently outperformed more complex models like XGBoost and Random Forest, achieving the lowest Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) on both cross-validation and test sets. Key findings indicate that population-related features, such as total population and labor force participation, are the most influential predictors. However, errors are larger for cities with non-linear population trends and high variability, highlighting the need for future improvements in feature engineering (e.g., trend terms or interaction terms) and model selection.

The project contributes to urban studies by emphasizing census data over remote sensing techniques, demonstrating how socioeconomic indicators can enhance the predictive accuracy of population models. All code, preprocessing steps, and analysis pipelines are fully reproducible, with additional insights provided on feature importance and residual patterns.
