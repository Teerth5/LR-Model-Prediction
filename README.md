# LR-Model-Prediction
Linear Regression model to predict a numerical value based on a single feature.


1. Residual Plot
Purpose: To analyze the residuals (the difference between observed and predicted values) and check for any patterns.
Insight: A good regression model should have residuals randomly scattered without clear patterns.
Implementation: Plotted the residuals against the predicted values. This helps identify any systematic errors or non-linear relationships.

2. Histogram of Residuals
Purpose: To check the distribution of residuals, ensuring they are normally distributed.
Insight: A normal distribution of residuals suggests that the model assumptions hold.
Implementation: The histogram of residuals helps verify if the errors are symmetrically distributed around zero.

3. Confidence Intervals for the Regression Line
Purpose: To visualize the uncertainty in the model’s predictions by plotting confidence intervals around the regression line.
Insight: Confidence intervals provide a range where the true regression line could lie with a certain probability (e.g., 95% confidence level).
Implementation: Added shaded regions to visualize the intervals, making it clear where predictions are more or less certain.

4. Learning Curve
Purpose: To visualize how the model’s performance (training and validation error) changes with the size of the training data.
Insight: This helps identify whether the model is overfitting or underfitting.
Implementation: The learning curve shows how well the model generalizes with more data, offering insights into its scalability and performance.
