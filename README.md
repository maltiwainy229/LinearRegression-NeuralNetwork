# LinearRegression-NeuralNetwork
A Machine Learning Project predicting house prices based on features like location, number of rooms, and property size using Linear Regression + Neural Network with TensorFlow

## Getting Started

To clone this repository, run:

```bash
git clone https://github.com/maltiwainy229/LinearRegression-NeuralNetwork.git
cd LinearRegression-NeuralNetwork
```

## Installation

Install all dependencies with pip:

```bash
pip install -r requirements.txt
```

## Dataset
The dataset is sourced from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) (House Prices - Advanced Regression Techniques).  
A training set is included in [`train.csv`](train.csv).

## Notebooks
- [`linRegression.ipynb`](linRegression.ipynb) - A baseline statistical model
- [`neurnet.ipynb`](neurnet.ipynb) - A deep learning approach for capturing non-linear relationships

Both models are evaluated using MAE, MSE, and R² score, with results compared to highlight trade-offs.
