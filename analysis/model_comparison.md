# Model Comparison

## Model 1: Simple Regression (Marketing Spend)

- **Dependent Variable:** Monthly Sales
- **Independent Variable:** Marketing Spend
- **R-Squared:** 0.1574
- **Adjusted R-Squared:** 0.1547
- **P-Value:** 0.000000
- **Business Usefulness:** Marketing spend has a statistically significant positive association with monthly sales but explains only a limited proportion of the variation.

---

## Model 2: Simple Regression (Footfall)

- **Dependent Variable:** Monthly Sales
- **Independent Variable:** Footfall
- **R-Squared:** 0.7348
- **Adjusted R-Squared:** 0.7340
- **P-Value:** 0.000000
- **Business Usefulness:** Footfall is a useful predictor of monthly sales and performs better than relying on marketing spend alone if supported by a higher R².

---

## Model 3: Multiple Regression

### Variables Used

- Marketing Spend
- Footfall
- Inventory Availability %
- Customer Rating
- Store Type (Mall Dummy)

### Model Performance

- **R-Squared:** 0.8077
- **Adjusted R-Squared:** 0.8045

### Significant Variables

- marketing_spend: Significant (p = 0.0000)
- footfall: Significant (p = 0.0000)
- inventory_availability_pct: Significant (p = 0.0000)
- customer_rating: Significant (p = 0.0318)
- store_type_Mall: Significant (p = 0.0222)


## Business Usefulness

The multiple regression model explains substantially more variation in monthly sales than either simple regression model because it considers multiple business drivers simultaneously.

## Limitations

- Regression identifies associations rather than causation.
- External factors such as economic conditions, promotions, seasonality, and competitor actions are not included.
- Results should support managerial decision-making alongside business judgment.
