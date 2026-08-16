# Applied-Predictive-Modeling
Applied predictive modeling with Elastic Net, Random Forest, and Gradient Boosting on a HackerRank cross-sectional dataset.

This project develops and compares predictive models for life expectancy using a set of socioeconomic, demographic, and country-level indicators.

The analysis includes data cleaning and preprocessing, model estimation, model selection, and evaluation of predictive performance.

## Models

The following models are considered:

- Elastic Net Regression
- Random Forest Regression
- Gradient Boosting Regression

Model hyperparameters are selected using grid search with five-fold cross-validation. Predictive performance is evaluated using Mean Absolute Error (MAE).

Among the models considered, Gradient Boosting provides the best cross-validation performance and is therefore used to generate predictions for the test dataset.

## Repository Structure

```text
├── Code/
│   └── Python notebook containing data preparation, model estimation,
│       cross-validation, and prediction
│
├── Data/
│   ├── Training dataset
│   └── Test dataset
│
├── Model and Results/
│   ├── PDF describing the data, methodology, models, and results
│   └── Gradient Boosting predictions for the test dataset
│
└── README.md
```

## Data

The `Data` folder contains two datasets:

- **Training data:** Contains the predictor variables and observed life expectancy used for model estimation and evaluation.
- **Test data:** Contains the predictor variables without observed life expectancy and is used to generate final predictions.

## Model Evaluation

Hyperparameters are selected using grid search with five-fold cross-validation. Model performance is evaluated using Mean Absolute Error (MAE).

## Results

Gradient Boosting achieves the lowest average cross-validation MAE among the models considered and is used to generate predictions for the test dataset.

The `Model and Results` folder contains:

- A PDF describing the data, modeling approach, and results.
- Predicted life expectancy values for the test dataset.
