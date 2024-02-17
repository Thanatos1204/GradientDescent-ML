Gradient Descent from Scratch
This repository contains Python code for implementing a Gradient Descent mechanism from scratch. Gradient Descent is a first-order iterative optimization algorithm for finding the minimum of a function. In this implementation, we focus on applying Gradient Descent to train a linear regression model.

Contents
Background
Requirements
Usage
Code Explanation
Background
Gradient Descent is a fundamental optimization algorithm used in machine learning and statistics. It iteratively updates the parameters of a model to minimize a loss function. In this implementation, we use Gradient Descent to train a linear regression model to predict tomorrow's maximum temperature based on today's maximum temperature.

Requirements
To run the code in this repository, you need:

Python 3.x
Required libraries: pandas, numpy, matplotlib, sklearn
You can install the required libraries using pip:

Copy code
pip install pandas numpy matplotlib scikit-learn
Usage
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/your-username/gradient-descent-from-scratch.git
Navigate to the project directory:
bash
Copy code
cd gradient-descent-from-scratch
Run the Python script:
Copy code
python gradient_descent.py
Code Explanation
The main components of the code are as follows:

Data Preprocessing: The code starts by loading a dataset containing weather data and preprocessing it, including handling missing values using forward filling.
Linear Regression: It demonstrates how to perform linear regression using scikit-learn and visualizes the linear relationship between the maximum temperature and tomorrow's maximum temperature.
Gradient Descent Implementation: The core of the code involves implementing Gradient Descent from scratch. It includes functions for forward propagation, computing mean squared error (MSE) loss, computing gradients, and backward propagation to update the model parameters.
Training Loop: The training loop iteratively updates the model parameters using Gradient Descent and evaluates the model's performance on a validation set.
