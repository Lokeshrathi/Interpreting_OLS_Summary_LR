# Interpreting_OLS_Summary_LR

# Important Note - This report is with respect to the Notebook present

### R-squared and Adjusted R-squared:

- If the values of Adjusted Rsqaured and R-sqaured is very different, it is a sign that A feauture/variable, might not be relevant to your model.

- Here no such problem occurs

### F - Statistic or F-test:
- It is used for assessing the overall significance of a model. In a Multiple LR, it compares the model with no predictors. 

- The Null hypothesis is that these 2 models are equal and Alternate Hypo is that the intercept only model is worse that our model.

- We get back a p-value as well as a statistic value, that helps us to select/reject Null hypothesis.

- In our case, **the p-value is very small (0.00) and high F-statistic value, therefore we reject our Null hypothesis and conclude that there is a Linear Relationship between F1,F2,F3 and the Target Variable.**

### T-test:

- Unlike f-test, **t-test compares each Features with the Target Variable and tells if there is a relationship between them.**

- Null hypothesis is that the feature variable coefficient is going to be 0 and The Alternate Hypothesis is that the Feature coefficient is not going to be 0.

- **Higher the t-test value, higher the chances that you reject the Null hypothesis. As per our model, the value is high and hence we reject the Null hypothesis (also p-value < 0.05 to reject the Null hypothesis).**

# I guess this repository gives you a good general idea on the Interpretition of OLS Regression Results.
