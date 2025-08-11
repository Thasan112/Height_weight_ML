# Height_weight_ML

Features
Data preprocessing with feature scaling (StandardScaler)

Linear Regression model for prediction

Simple and easy to understand code

Requirements
Python 3.x

scikit-learn
pandas 
numpy
Matplotlib


Results
Mean Squared Error: 22.795111961354205
Mean Absolute Error: 2.943216949404291
Root Mean Squared Error: 4.774422683566486

Ordinary Least Squares (OLS) regression summary for the model coefficient on height (x1)

| Variable | Coefficient | Std. Error | t-statistic | P-value | \[0.025 | 0.975] Confidence Interval |
| -------- | ----------- | ---------- | ----------- | ------- | ------- | -------------------------- |
| x1       | 16.9265     | 38.391     | 0.441       | 0.665   | -64.071 | 97.92                      |


Interpretation:

The coefficient for height (x1) is approximately 16.93.

The large standard error (38.39) and high p-value (0.665) indicate this coefficient is not statistically significant at typical levels.

The confidence interval includes zero, further supporting the insignificance of this predictor in the current model.
