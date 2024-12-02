# Car Price Prediction with Linear Regression

## Project Overview

In this project, I applied a **Linear Regression** model to a car dataset to predict the **selling price** of cars based on various features. The dataset includes variables such as:

- **Car model**
- **Year**
- **Current price**
- **Kilometers driven**
- **Fuel type**
- **Seller type**
- **Transmission type**
- **Number of owners**

The goal was to implement the model and enhance its performance by addressing key **assumptions**, **preprocessing** steps, and **optimization techniques**.

---

## Key Tasks & Steps

### 1. **Dataset Exploration**
- **Loaded a dataset** with features like:
  - Car model, year, selling price, present price, kilometers driven, fuel type, seller type, transmission, and number of owners.
  
### 2. **Regression Assumptions**
- **Checked for key assumptions** in linear regression:
  - **Linearity**: Ensured linear relationships between independent and dependent variables.
  - **Homoscedasticity**: Verified constant variance of residuals.
  - **Normality of residuals**: Ensured that residuals were approximately normally distributed.
  - ** No Perfect Multicollinearity *: used variance inflation factor(VIF) to ensure no multicollinearity.
  -  ** NO Autocorrelation **: used durbin_watson test to make sure no autocorrelation
  
- **Implemented various transformations** (such as scaling features) and explored techniques like **Standard Scaling** to improve model performance.

### 3. **Modeling & Performance Tuning**
- **Implemented a linear regression model** and evaluated its performance.
- **Improved model accuracy** through techniques such as **feature engineering**.
- **Explored additional regression models** and compared their results with the linear regression model.

### 4. **Optimization**
- Focused on **optimizing the model** by:
  - **Tuning parameters** to improve results.
  - Evaluating performance using metrics like **R-squared**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)**.

---

## Outcome

The project helped me gain hands-on experience in:
- Applying **regression techniques** to real-world data.
- **Exploring model assumptions** to ensure accurate results.
- **Optimizing the model** through parameter tuning and evaluating performance metrics.
- Enhancing my understanding of **data preprocessing**, especially scaling and transforming features, to improve model performance.

---
