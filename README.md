# Backpropagation Implementation with NUMPY
This project provides an overview and guidance for implementing backpropagation from scratch using the MNIST dataset. Backpropagation is a fundamental algorithm for training neural networks, and this implementation focuses on applying it to the MNIST handwritten digit recognition task.

## Introduction
Backpropagation is a key algorithm in training neural networks. This implementation focuses on applying backpropagation to the MNIST dataset, a popular dataset for handwritten digit recognition.

## Dependencies
- Python (>=3.6)
- NumPy
- Matplotlib (for visualization)

## Getting Started
Clone the repository:

```bash
git clone https://github.com/ChieBKAI/backpropagation-implementation-from-scratch.git
cd backpropagation-mnist
```

## Backpropagation Overview
Backpropagation is a supervised learning algorithm used for training artificial neural networks. It involves computing gradients of the loss with respect to the model parameters, allowing for parameter updates through gradient descent.

The key steps of backpropagation include:

1. Forward Pass: Compute the predicted output by propagating input through the neural network.

2. Loss Calculation: Compute the loss between the predicted output and the ground truth.

3. Backward Pass (Backpropagation): Compute gradients of the loss with respect to the model parameters using the chain rule.

4. Parameter Update: Update the model parameters using an optimization algorithm (e.g., gradient descent).

![Backpropagation visualization](https://developer-blogs.nvidia.com/wp-content/uploads/2022/02/DS-Guide-to-Gradient-Descent_Pic5.gif)

## References
- [Building a neural network FROM SCRATCH](https://www.youtube.com/watch?v=w8yWXqWQYmU)
- [Neural Network from Scratch](https://www.youtube.com/watch?v=pauPCy_s0Ok)
