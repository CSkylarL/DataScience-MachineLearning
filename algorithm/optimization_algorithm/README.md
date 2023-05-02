# Optimization Methods in Machine Learning

Optimization methods play a crucial role in machine learning, as they are used to minimize the loss function or error of the learning algorithms. These methods help to find the optimal set of parameters for a given model, resulting in the best possible performance on the given task. This repository contains examples and explanations of below optimization methods used in machine learning.

1. [**Gradient Descent**](./gradient_descent.ipynb): Gradient descent is a first-order optimization algorithm that iteratively adjusts the model's parameters in the direction of the steepest decrease in the loss function. It is a widely-used optimization method for various machine learning algorithms, particularly in deep learning. There are several variants of gradient descent:
    - **Batch Gradient Descent**: The gradient is computed using the entire dataset, which can be slow for large datasets but provides accurate parameter updates.
    - **Stochastic Gradient Descent (SGD)**: The gradient is computed using a random sample from the dataset, resulting in faster optimization but noisier updates.
    - **Mini-batch Gradient Descent**: The gradient is computed using a small batch of samples from the dataset, striking a balance between the speed of stochastic gradient descent and the accuracy of batch gradient descent.
