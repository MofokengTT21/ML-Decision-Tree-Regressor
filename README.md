## Decision Tree Regression for Predicting Meadian Value of Owner-occupied Homes.
[View](https://mofokengtt21.github.io/ml-decision-tree-reg/)
### Overview:
This project explores the application of decision tree regression to predict **median value** of owner-occupied homes. Decision trees are powerful non-parametric models that are capable of capturing complex relationships in the data, making them suitable for regression tasks.

### Key Features:
- Utilizes housing data sourced from (https://gist.github.com/inoccu/139294a0476751fbfd1cde4110edbbab).
- Implements a DecisionTreeRegressor model from scikit-learn library for regression.
- Evaluates model performance using commonly used regression metrics such as RMSE (Root Mean Squared Error), MAE (Mean Absolute Error), and R² (Coefficient of Determination).
- Visualizes the performance of the regression model through a scatter plot of actual vs. predicted values.

### Steps Involved:
1. **Data Sourcing**: Data is sourced for predicting meadian value of homes.
2. **Data Preprocessing**: The data is split into training and test sets.
3. **Model Training**: A DecisionTreeRegressor model is trained on the training data.
4. **Model Evaluation**: The performance of the model is evaluated using RMSE, MAE, and R² metrics.
5. **Visualization**: The actual vs. predicted values are visualized using a scatter plot.

### Results:
The decision tree regression model achieves **(RMSE):** 4.274, **(MAE):** 2.963, **R^2 Score:** 0.793, indicating the model is able to make accurate predictions for most of the data points, but there are some cases where the predictions are less accurate.

### Future Improvements:
- Experiment with different hyperparameters of the decision tree model to optimize performance.
- Explore ensemble methods such as Random Forest or Gradient Boosting for potentially improved results.
- Incorporate additional features or datasets to enhance model predictions.

