# Magic The Gathering (MTG) Card Price Predictor

The project uses regression techniques to estimate the price of creature-typed Magic the Gathering cards. It further classifies each card by its value, determining if it's priced above or below $1. This categorization aids players in budget-focused decisions during the period after an expansion releases when card prices fluctuate rapidly. The project is purposed to inform players about the possible stabalized price of a card and to aid in making card purchasing decisions.

## Table of Contents

- [Overview](#overview)
- [Models Used](#models-used)
- [Installation](#installation)

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
3. Run the Jutyter Notebook
