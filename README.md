# Real estate forecasting model

RealEstateAI Solutions aims to optimize the real estate prices evaluation through the use of advanced regularization techniques in linear regression models. The objective is to provide more accurate and reliable price forecasts, reducing the risk of overfitting and improving the generalization capability of the model.

In real estate, getting accurate estimates of property prices is crucial to making informed decisions. However, traditional linear regression models may suffer from overfitting, compromising the accuracy of predictions. It is necessary to explore effective regularization methods to improve predictive performance and manage the complexity of the model.

By implementing and comparing regularization methods such as Lasso, Ridge and Elastic Net, RealEstateAI Solutions will offer a system that can provide more accurate and stable real estate price forecasts. This will allow real estate agents and investors to make decisions based on more reliable data, increasing their competitiveness in the market.

**Project Requirements:**

1. **Dataset preparation:**
    - Loading and pre-processing of real estate price data.
    - Management of missing values, coding of categorical variables and data normalization/scaling.
2. **Regression Models Implementation:**
    - **Ridge Regression:** Model implementation and training with Ridge regularization.
    - **Lasso Regression:** Model implementation and training with Lasso regularization.
    - **Elastic Net Regression:** Model implementation and training with Elastic Net regularization.
3. **Performance Evaluation:**
    - Use of cross-validation techniques.
    - Calculation of the Mean Squared Error (MSE) for each model.
    - Comparison of model complexity by estimating the number of non-zero coefficients.
    - Analysis and comparison of the results of the various regularization methods.
4. **Display of results:**
    - Create charts to view and compare model performance.
    - Visualization of residue distribution to assess the adequacy of the model.

# The dataset

The dataset is available here: https://proai-datasets.s3.eu-west-3.amazonaws.com/housing.csv (freely taken from the following dataset: https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)

- **price:** the price, the target to be expected
- **area:** surface of the property
- **bedrooms:** number of bedrooms
- **bathrooms:** number of bathrooms
- **stories:** number of floors
- **mainroad:** 1 if the property faces a main road, 0 otherwise
- **guestroom:** 1 if the property has a guest room, 0 otherwise
- **basement:** 1 if the property has a basement, 0 otherwise
- **hotwaterheating:** 1 if the property has a boiler, 0 otherwise
- **airconditioning:** 1 if the property has air conditioning, 0 otherwise
- **parking:** number of car parks
- **area:** 1 if the property is in a prestigious area, 0 otherwise
- **furnishingstatus:** 0 if the property is unfurnished, 1 if it is partially furnished, 2 if it is fully furnished
