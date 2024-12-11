# DataCamp Tests

This repository contains scripts and datasets used for various DataCamp tests and projects.

## Project Structure

- `Cheat_sheets/`: Contains Jupyter notebooks with cheat sheets and examples of models.
- `Datasets/`: Contains various datasets used in the projects.
    - `Real Estate/`: Contains datasets related to real estate.
    - `DVD_rental/`: Contains datasets related to DVD rentals.
    - `Coffeeshops/`: Contains datasets related to coffee shops.
    - `Credit_card_approvals/`: Contains datasets related to credit card approvals.
- `Rental_days_pred.ipynb`: Jupyter notebook for predicting rental days using different regression models.

## Notebooks

### Rental_days_pred.ipynb

This notebook includes the following steps:

1. **Data Preparation**:
    - Dropping unnecessary columns.
    - Splitting the dataset into training and test sets.

2. **Model Training and Evaluation**:
    - Linear Regression
    - Lasso Regression
    - Random Forest Regressor

3. **Model Fine-Tuning**:
    - Using GridSearchCV to find the best parameters for the Random Forest Regressor.

## How to Use

1. Clone the repository:
   ```sh
   git clone https://github.com/RazDwa1923/DataCamp_Tests.git