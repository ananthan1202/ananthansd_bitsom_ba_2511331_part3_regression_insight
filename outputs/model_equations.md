# Model Equations

1. Simple Regression Equations

Model 1: Marketing Spend → Monthly Sales

Equation:

Monthly Sales = 446410.58 + 35.68 × Marketing Spend

Interpretation

- Intercept (446410.58): Estimated monthly sales when marketing spend is zero.
- Marketing Spend coefficient (35.68): Every additional 1 unit spent on marketing is associated with an increase of about 35.68 units in monthly sales.

---

Model 2: Footfall → Monthly Sales

Equation:

Monthly Sales = 560777.35 + 2.13 × Footfall

Interpretation

- Intercept (560777.35): Estimated monthly sales when footfall is zero.
- Footfall coefficient (2.13): Every additional customer visiting the store is associated with an increase of approximately 2.13 units in monthly sales.

---

2. Multiple Regression Equation

Monthly Sales =

131460.31

+ 1.186 × Marketing Spend
+ 33.87 × Footfall
+ 2818.21 × Inventory Availability %
+ 10547.38 × North
+ 21940.49 × South
+ 17491.37 × West

---

3. Explanation of Each Coefficient

- Intercept: Baseline monthly sales when all independent variables are zero.
- Marketing Spend: Increasing marketing spend is positively associated with higher monthly sales.
- Footfall: Stores with more customer visits generally achieve higher sales.
- Inventory Availability %: Better product availability is associated with increased sales because customers are more likely to find the products they need.
- North: Represents the change in sales for stores in the North region compared with the reference region. This variable was not statistically significant.
- South: Stores located in the South region are expected to have higher monthly sales than the reference region.
- West: Stores located in the West region are expected to have higher monthly sales than the reference region.

---

4. Explanation of Dummy Variables

The region variable was converted into dummy variables.

- North = 1 if the store is in the North region, otherwise 0.
- South = 1 if the store is in the South region, otherwise 0.
- West = 1 if the store is in the West region, otherwise 0.

These variables measure the effect of store location on monthly sales.

---

5. Reference Category Used

The East region was used as the reference category.

Therefore:

- North, South, and West coefficients represent their difference compared with East.

---

6. Final Model Selected

The Multiple Regression Model was selected as the final model.

---

7. Reason for Selecting the Final Model

The multiple regression model was selected because it explains the highest proportion of variation in monthly sales.

- R² = 0.8114, meaning the model explains approximately 81.14% of the variation in monthly sales.
- Marketing Spend, Footfall, Inventory Availability, South, and West are statistically significant predictors.
- The model considers multiple business factors simultaneously, making it more useful for forecasting and business decision-making than either simple regression model.
