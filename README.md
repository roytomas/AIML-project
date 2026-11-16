# AIML Project

This repository contains a small machine learning project focused on understanding and visualizing gradient descent for a simple linear regression model.

## Overview

The project demonstrates how a model learns the best values for its parameters by minimizing a cost function. It includes:

- a Jupyter notebook for implementing and visualizing gradient descent
- helper utilities for plotting model behavior and optimization steps
- examples of cost and gradient calculations for linear regression

## Project files

- `gradient-descent.ipynb` — notebook that loads the training data, computes the cost and gradient, and runs gradient descent
- `lab_utils_uni.py` — plotting and visualization utilities used by the notebook
- `lab_utils_common.py` — shared helper functions and reusable code
- `README.md` — project documentation

## Objectives

This project is intended to help learn:

- how linear regression works
- how cost functions are calculated
- how gradients are computed
- how gradient descent updates model parameters over time
- how optimization behavior can be visualized in practice

## Requirements

To run the notebook, you will need:

- Python 3
- NumPy
- Matplotlib
- Jupyter Notebook or JupyterLab

Install dependencies with:

```bash
pip install numpy matplotlib notebook
```

## Run the project

Open the notebook in Jupyter:

```bash
jupyter notebook gradient-descent.ipynb
```

Then run the cells in order to see the training process and optimization results.

## License

This project is provided for educational purposes.
