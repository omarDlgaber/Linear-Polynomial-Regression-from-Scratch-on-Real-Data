# Linear & Polynomial Regression on Real Data 🏡📈

## Overview
This repository provides a comprehensive, hands-on implementation of Linear and Polynomial Regression using **real-world data** rather than synthetic examples. We use the **California Housing** dataset (containing over 20,640 actual records) to understand how these algorithms work under the hood and how to implement them practically.

## Project Goals & Contents
The Jupyter Notebook (`Linear_&_Polynomial_Regression_on_Real_Data.ipynb`) covers the following key concepts:

1. **Loading & Exploring Data:** Reading the California Housing dataset and analyzing correlations between different features and house prices.
2. **Building from Scratch:** Implementing Linear Regression manually using Gradient Descent to understand the underlying mathematics.
3. **Polynomial Regression:** Applying more complex polynomial models and observing the phenomenon of overfitting.
4. **Comparing Optimizers:** Testing and evaluating the performance of various optimization algorithms, including:
   - Batch Gradient Descent
   - Stochastic Gradient Descent (SGD)
   - Mini-batch GD
   - Momentum
   - RMSprop
   - Adam
   - AdamW (Adam with weight decay)
5. **Professional Implementations:** Comparing the performance and results of our from-scratch models with industry-standard libraries like **Scikit-Learn** and **PyTorch**.

## Requirements
To run the notebook successfully, you will need the following libraries installed:
- Python 3.x
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-Learn
- PyTorch

You can install the required packages using pip:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn torch
```
## How to Use
1. Clone this repository:
```bash
git clone [https://github.com/omarDlgaber/Linear-Polynomial-Regression-from-Scratch-on-Real-Data.git](https://github.com/omarDlgaber/Linear-Polynomial-Regression-from-Scratch-on-Real-Data.git)
```
2. Navigate to the project directory and open the Jupyter Notebook:
```bash
jupyter notebook "Linear_&_Polynomial_Regression_on_Real_Data.ipynb"
```
3. Run the cells sequentially to explore the data, train the models, and view the visual comparisons.

## Conclusion
Building machine learning models from scratch provides a deep mathematical understanding of cost functions and weight updates. However, the project also highlights the power, efficiency, and speed of professional libraries like Scikit-Learn (which uses the Normal Equation for instant results) and PyTorch for advanced optimization.
