# Economic-Freedom-of-The-World-Regression-Analysis

### This project analyzes the factors influencing economic freedom of the world using an Ordinary Least Squares (OLS) regression model. Key economic indicators such as government consumption, market openness, and capital movement controls are used to predict the Economic Freedom Summary Index.

Key Features:
- Data Cleaning and Preprocessing: Handled missing values, converted data types, and addressed multicollinearity using Variance Inflation Factor (VIF).
- Regression Model: Built and optimized an OLS regression model with a final R-squared of 0.70, predicting economic freedom based on selected variables.
- Model Evaluation: Performed extensive residual diagnostics to verify model assumptions, including tests for normality, homoscedasticity, and autocorrelation (Durbin-Watson test).
- Cross-Validation: Implemented k-fold cross-validation to evaluate model performance and prevent overfitting.
- Feature Selection: Removed statistically insignificant variables to improve model interpretability and prediction accuracy.
- Visualization and Reporting: Provided visualizations and statistical summaries to communicate insights, including the significant impact of market openness on economic freedom.
- Tools and Libraries:
Python: pandas, statsmodels, scikit-learn, matplotlib, seaborn
- Data: https://www.fraserinstitute.org/economic-freedom/dataset?geozone=world&page=dataset&min-year=2&max-year=0&filter=0 
