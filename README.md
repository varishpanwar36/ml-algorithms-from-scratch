# Machine Learning Algorithms from Scratch

Implementations of core machine learning algorithms using NumPy, each compared against scikit-learn.

## Notebooks
- `GD_Regressor_Class.ipynb`: Linear Regression with batch gradient descent
- `SGD_Regressor_Class.ipynb`: Linear Regression with stochastic gradient descent and learning-rate decay
- `MBGD_Regressor_Class.ipynb`: Linear Regression with mini-batch gradient descent
- `RidgeRegression_from_Scratch.ipynb`: Ridge Regression using the closed-form solution and gradient descent
- `Logistic_Regression_from_Scratch.ipynb`: Logistic Regression, from the perceptron trick to the sigmoid function to log-loss gradient descent, with decision-boundary plots

## Details
- Regression notebooks use scikit-learn's diabetes dataset and are checked against scikit-learn using R² score.
- Logistic Regression uses a synthetic dataset from `make_classification`.
- Libraries: Python, NumPy, scikit-learn, Matplotlib.

## How to run
Open any notebook in Google Colab or Jupyter and run all cells.
