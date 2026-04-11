# ML Regression Notes

## 1. Linear Regression

Linear regression is a statistical method to predict the relationship between a dependent variable and one or more independent variables, utilizing a linear equation.

### Mathematical Formula:
$Y = \beta_0 + \beta_1X_1 + \beta_2X_2 + ... + \beta_nX_n + \epsilon$

**Emoji:** 📈

## 2. Loss Functions

Loss functions measure how well a model's predictions match the actual data. The most commonly used loss function in linear regression is Mean Squared Error (MSE).

### Mathematical Formula:
$MSE = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2$

**Emoji:** ⚖️

## 3. Optimization

Optimization involves finding the best parameters for the model that minimize the loss function. Gradient descent is a popular optimization algorithm.

### Mathematical Formula:
$\theta := \theta - \alpha \nabla J(\theta)$

**Emoji:** ⛰️

## 4. Assumptions

Linear regression makes several assumptions, including:
- Linearity: The relationship between the variables is linear.
- Independence: Observations are independent.
- Homoscedasticity: Constant variance of errors.
- Normality: Errors are normally distributed.

**Emoji:** 📜

## 5. Regularization

Regularization techniques such as Lasso and Ridge regression help to prevent overfitting by adding a penalty to the loss function.

### Mathematical Formula:
$Lasso: J(\theta) = MSE + \lambda \sum |\theta_i|

Ridge: J(\theta) = MSE + \lambda \sum \theta_i^2$

**Emoji:** 🛡️

## 6. Bias-Variance Tradeoff

The bias-variance tradeoff is the balance between model complexity and error. A high-bias model may underfit, while a high-variance model may overfit.

**Emoji:** ⚖️

## 7. Diagnostics

Diagnostic plots can help to identify issues such as non-linearity and outliers in the data. Common plots include residual plots and Q-Q plots.

**Emoji:** 🔍

## 8. Edge Cases

Edge cases, such as multicollinearity and heteroscedasticity, can significantly affect the model's performance and should be monitored.

**Emoji:** ⚠️

## 9. Interview Questions

- What is the difference between Lasso and Ridge regression?
- When would you use linear regression?
- How do you interpret the coefficients?

**Emoji:** 💬

## 10. Practical Applications

Linear regression is widely used in various fields, including finance, marketing, and the social sciences.

**Emoji:** 🌍

## 11. Key Takeaways

- Understand the assumptions of linear regression.
- Use regularization to prevent overfitting.
- Always assess your model's performance and diagnostics.

**Emoji:** 🏆