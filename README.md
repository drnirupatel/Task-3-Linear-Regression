# Task 3: Linear Regression

## Objective
To implement and understand Simple and Multiple Linear Regression using Scikit-Learn for house price prediction.

## Dataset
Housing Price Dataset (Housing.csv)

- Total Records: 545
- Target Variable: price
- Features include:
  - area
  - bedrooms
  - bathrooms
  - stories
  - parking
  - mainroad
  - guestroom
  - basement
  - airconditioning
  - prefarea
  - furnishingstatus

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## Methodology

### 1. Data Loading
Loaded the Housing.csv dataset using Pandas.

### 2. Data Preprocessing
- Checked dataset structure and statistics.
- Converted categorical variables into numerical format using One-Hot Encoding (`pd.get_dummies()`).

### 3. Train-Test Split
- Training Data: 80%
- Testing Data: 20%

### 4. Model Training
Implemented Linear Regression using Scikit-Learn.

### 5. Model Evaluation
Evaluated the model using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### 6. Visualization
- Actual vs Predicted Price Plot
- Simple Linear Regression Plot (Area vs Price)

## Results

| Metric | Value |
|----------|----------|
| MAE | 970043.40 |
| MSE | 1754318687330.66 |
| R² Score | 0.6529 |

## Interpretation

- The model explains approximately 65.3% of the variation in housing prices.
- Area, bathrooms, parking, and other housing features significantly influence house prices.
- Multiple Linear Regression performed better than Simple Linear Regression because it considers multiple factors simultaneously.

## Conclusion

This project successfully implemented both Simple and Multiple Linear Regression models for house price prediction. The Multiple Linear Regression model achieved an R² score of 0.653, indicating a reasonable predictive performance. The task provided practical experience in data preprocessing, model training, evaluation, and interpretation of regression results.
