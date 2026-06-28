# Regression-Based Business Insights

## Project Overview

This project analyzes the factors associated with monthly sales across retail stores using linear regression techniques. The objective is to identify the business variables that have the strongest relationship with sales and provide practical recommendations for management.

---

## Business Problem

The retail leadership team wants to understand which operational and business factors influence monthly sales. The findings from this analysis can support decisions related to marketing investment, inventory management, staffing, and store operations.

---

## Dataset

The dataset contains monthly store-level information including:

- Marketing Spend
- Footfall
- Average Discount Percentage
- Staff Count
- Inventory Availability
- Competitor Distance
- Holiday Flag
- Customer Rating
- Store Type
- Region
- Monthly Sales
- Monthly Profit

---

## Dependent Variable

- Monthly Sales

---

## Independent Variables

The analysis considered several predictors, including:

- Marketing Spend
- Footfall
- Inventory Availability
- Customer Rating
- Store Type (Dummy Variables)
- Region (Dummy Variables)

Store ID and Month were excluded from regression because they are identifiers rather than explanatory variables.

Monthly Profit was not included because it is closely related to Monthly Sales and could introduce data leakage.

---

## Data Preparation

The dataset was cleaned before analysis by:

- Removing leading and trailing spaces
- Removing extra spaces within text values
- Standardizing text to Proper Case
- Formatting the Month column consistently
- Removing duplicate records
- Removing records with missing values
- Creating dummy variables for categorical features

Reference Categories:

- Store Type → Airport
- Region → East

---

## Regression Approach

Three regression models were developed.

### Model 1

Monthly Sales ~ Marketing Spend

R² = 0.1574

---

### Model 2

Monthly Sales ~ Footfall

R² = 0.7348

---

### Model 3

Multiple Linear Regression using:

- Marketing Spend
- Footfall
- Inventory Availability
- Customer Rating
- Store Type (Mall Dummy)

R² = 0.8077

---

## Model Comparison

The multiple regression model explains more variation in monthly sales than either simple regression model because it evaluates multiple business drivers simultaneously.

---

## Final Model Selected

The multiple regression model was selected because it provides the strongest explanatory power and is more suitable for business decision-making.

---

## Business Recommendation

Management should focus on improving the business drivers that showed a meaningful relationship with monthly sales, while avoiding decisions based on a single metric. Marketing activities, customer traffic, inventory management, and store characteristics should be evaluated together.

---

## Assumptions and Limitations

- Regression identifies association, not causation.
- The analysis is based on the available dataset only.
- External influences such as local market conditions, seasonality, and competitor actions were not included.

---

## Repository Structure

---

## Tools Used

- Google Colab
- Python
- Pandas
- Statsmodels
- OpenPyXL
- Matplotlib

---

## Screenshots Included

- Simple Regression Output
- Multiple Regression Output
- Residual Analysis
- Model Comparison
