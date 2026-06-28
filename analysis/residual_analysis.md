# Residual Analysis

## Model Used

Multiple Linear Regression

## Residual Calculation

Residual = Actual Monthly Sales − Predicted Monthly Sales

---

## Top 5 Positive Residuals

|   monthly_sales |   Predicted_Sales |   Residual |
|----------------:|------------------:|-----------:|
|          799047 |            692246 |   106801   |
|          713611 |            608679 |   104933   |
|          686738 |            593918 |    92819.5 |
|          787716 |            694932 |    92783.3 |
|          763162 |            670568 |    92594.4 |

Positive residuals indicate stores where actual sales exceeded model expectations.

---

## Top 5 Negative Residuals

|   monthly_sales |   Predicted_Sales |   Residual |
|----------------:|------------------:|-----------:|
|          685379 |            831376 |    -145997 |
|          627172 |            756317 |    -129145 |
|          595468 |            720007 |    -124540 |
|          641865 |            761513 |    -119648 |
|          415722 |            522721 |    -106999 |

Negative residuals indicate stores where actual sales were below model predictions.

---

## Business Interpretation

Positive residuals may indicate exceptional local demand, successful promotions, or operational advantages that are not captured by the regression model.

Negative residuals may indicate operational issues, competitive pressures, or temporary disruptions that reduced sales.

The residual distribution suggests that additional explanatory variables could further improve predictive performance.
