# Perceptron Learning Algorithm - Python Implementation
This project implements the Perceptron Learning Algorithm using NumPy for numerical operations. It’s a basic machine learning model used for binary classification, and this example demonstrates how it learns from data through iterative weight updates.

###  What is the Perceptron Algorithm?
The Perceptron is the simplest type of feedforward neural network. It’s used for binary classification — classifying data into two categories (0 or 1).

Key ideas:

- Takes inputs (features), applies weights and a bias

- Passes the result through a step function (activation)

- Adjusts weights based on prediction error

- It learns by minimizing errors over multiple training iterations (epochs)

### What This Code Does
- I use a sample dataset with 3 features: age, income, and salary

- Initializes random weights and a bias

- It runs the Perceptron training loop over several epochs

**Prints:**

- Weighted sum of inputs

- Prediction vs target

- Updated weights and bias after each data point

- Makes a final prediction on an unseen input

**Output**

During training:
- We can see how weights and bias adjust after each sample.

- Final prediction for a test input is printed.


