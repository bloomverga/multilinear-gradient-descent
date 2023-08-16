# Implementing Gradient Descent for Linear Regression
In this repo, we implemented Gradient Descent to determine parameters w and b of a Linear Regression model.
The code contains the following files:
- `Multi Linear Gradient Descent.ipynb` the notebook containing the main code to execute. In this notebook, we implemented 
  - `compute_cost(X, y, w, b)` to calculate the squared error cost from feature `X`, target value `y` and parameters `w` and `b`.
  - `compute_gradient(X, y, w, b)` to compute each gradients of the cost with respect to parameter `w` and parameter `b`.
  - `gradient_descent(X, y, w_in, b_in, alpha, num_iters, f_compute_costs, f_compute_gradients)` which implements the gradient descent algorithm in order to find the value of parameters `w` and `b` for which the cost is minimal/near to a minimal.

- `deeplearning.mplstyle` a matploblip styling file 
- `lab_utils_uni.py` a file containing some utility functions for ploting, in order to visualize linear regression training.

> _This repo is relative to my personnal implementation of Multilinear Gradient Descent in Coursera ML Specialisation, Course 1._