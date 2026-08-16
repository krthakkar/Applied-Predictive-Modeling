# Machine Learning-Based Predictive Modeling
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

- **`Data`** — Training and test datasets used for the predictive modeling exercise.

- **`Code`** — Python notebook containing data preparation, preprocessing, model estimation, cross-validation, model comparison, and prediction.

- **`Model and Results`** — PDF describing the data, methodology, predictive models, and results, along with the Gradient Boosting predictions for the test dataset.
