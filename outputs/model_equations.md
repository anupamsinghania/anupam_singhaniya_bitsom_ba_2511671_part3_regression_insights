# Model Equations

## Simple Regression Model 1

**Dependent Variable:** Monthly Sales

**Independent Variable:** Marketing Spend

### Equation

Monthly Sales = 567463.56 + (2.0519 × Marketing Spend)

### Business Interpretation

For every one-unit increase in marketing spend, monthly sales are expected to increase by approximately 2.05 units on average, assuming all other factors remain unchanged.

---

## Simple Regression Model 2

**Dependent Variable:** Monthly Sales

**Independent Variable:** Footfall

### Equation

Monthly Sales = 447699.03 + (35.6415 × Footfall)

### Business Interpretation

Higher customer footfall is associated with higher monthly sales. The coefficient estimates the average increase in monthly sales for every additional customer visit.

---

## Multiple Regression Model

### Equation

Monthly Sales =
97583.00

 + (1.1846 × marketing_spend)
 + (33.7347 × footfall)
 + (2836.1700 × inventory_availability_pct)
 + (10694.2739 × customer_rating)
 + (14027.9754 × store_type_Mall)

---

## Coefficient Interpretation

Each coefficient estimates the expected change in monthly sales when that variable increases by one unit while all other variables remain constant.

A positive coefficient indicates a positive relationship with monthly sales.

A negative coefficient indicates an inverse relationship with monthly sales.

---

## Dummy Variables

Dummy variables were created for the categorical variables using one category as the reference group.

### Store Type

Reference Category:
- Airport

Dummy Variables:
- High Street
- Mall
- Residential

### Region

Reference Category:
- East

Dummy Variables:
- North
- South
- West

Each dummy coefficient compares that category against the reference category.

---

## Final Model Selected

The Multiple Regression model was selected because it considers several business drivers at the same time instead of relying on a single predictor.

It provides a stronger explanation of monthly sales and is more useful for business decision-making than either simple regression model.
