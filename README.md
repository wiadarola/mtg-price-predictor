# Magic The Gathering (MTG) Card Price Predictor

Predict the price of MTG cards using various regression models and also classify if a card will be priced above or below $1.

## Table of Contents

- [Overview](#overview)
- [Models Used](#models-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

Magic The Gathering is one of the most popular trading card games. This repository aims to predict the price of an MTG card using historical data and various machine learning models. Additionally, we also classify cards into budget (below $1) and non-budget (above $1) categories, which can be helpful for players building on a budget.

## Models Used

1. **Linear Regression:** Basic linear regression model to predict the continuous price of a card.
2. **Linear Regression with Ridge Regularization:** Linear regression model with Ridge regularization to prevent overfitting.
3. **Linear Regression with Lasso Regularization:** Linear regression model with Lasso regularization for feature selection and to prevent overfitting.
4. **Logistic Regression:** Classification model to predict if a card will be above or below $1.
5. **Support Vector Machine (SVM):** Another classification model to predict the budget category of a card.

## Installation

1. Clone this repository:
git clone https://github.com/your_username/mtg-price-predictor.git
2. Navigate to the directory:
cd mtg-price-predictor
3. Install the required libraries:
pip install -r requirements.txt

## Usage

1. Train the models:
python train.py
2. To predict the price or category of a card:
python predict.py --model [model_name] --input [path_to_input_data]
Replace `[model_name]` with the model of your choice (linear, ridge, lasso, logistic, svm) and `[path_to_input_data]` with the path to your input data file.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues](https://github.com/your_username/mtg-price-predictor/issues) page.

## License

MIT License. See `LICENSE` for more information.
