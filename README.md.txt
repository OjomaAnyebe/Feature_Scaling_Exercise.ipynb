# Feature Scaling with sklearn - Exercise Solution

This repository contains my solution to a multiple linear regression exercise that includes **feature scaling** as part of the preprocessing steps. It is part of my data science learning journey on Udemy, where I am deepening my understanding of regression analysis and feature scaling techniques.

---

## About the Exercise

### Dataset:
The dataset provided, `real_estate_price_size_year.csv`, includes information about real estate properties, such as:
- **Dependent Variable (Target):**
  - `price`: The selling price of the property.
- **Independent Variables (Features):**
  - `size`: The size of the property in square feet.
  - `year`: The year the property was constructed.

### Objectives:
1. **Build a Multiple Linear Regression Model**:
   - Predict property prices based on size and construction year.
2. **Standardize the Data**:
   - Apply feature scaling to ensure variables are on the same scale.
3. **Perform Analysis**:
   - Display model intercept and coefficients.
   - Compute R-squared and adjusted R-squared values.
   - Compare this model with the simple linear regression (using only `size` as the predictor).
4. **Make Predictions**:
   - Estimate the price of a 750 sq.ft. apartment built in 2009.
5. **Assess Statistical Significance**:
   - Find and interpret p-values for the independent variables.
6. **Summarize Findings**:
   - Create a concise summary table of the results.

---

## Tools and Libraries Used

This exercise utilizes the following Python libraries:
- **`numpy`**: For numerical computations.
- **`pandas`**: For data manipulation and analysis.
- **`matplotlib` and `seaborn`**: For visualizing data relationships.
- **`sklearn`**: For regression modeling and feature scaling.

---

## Key Highlights of the Exercise

1. **Feature Scaling**:
   - Standardized the dataset to improve model performance and ensure coefficients are comparable.

2. **Regression Analysis**:
   - Built and evaluated a multiple linear regression model.
   - Compared metrics like R-squared and adjusted R-squared between models.

3. **Prediction**:
   - Used the model to estimate property prices for specified inputs.

4. **Statistical Significance**:
   - Examined p-values to determine the importance of each predictor.