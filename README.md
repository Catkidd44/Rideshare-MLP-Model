# 🚗 Rideshare Price Prediction with an MLP
This project tests how well a simple Multi-Layer Perceptron (MLP) can predict rideshare prices using structured trip data. I wanted to see if a neural network could pick up on nonlinear relationships that linear models like Ridge Regression might miss.

The dataset includes common rideshare features like trip distance, duration, and weather or time-related variables.
I cleaned, scaled, and encoded the data before training both a Ridge model and an MLP using scikit-learn.
Everything was built and evaluated inside a Jupyter Notebook for full transparency.

Ridge Regression served as the baseline. It helps establish how far a linear model can go with regularization.

MLP Regressor was used to model nonlinear interactions. I experimented with hidden layers, activation functions, and learning rates to find a setup that balanced bias and variance.

The main goal was to compare interpretability and performance - linear vs neural.
