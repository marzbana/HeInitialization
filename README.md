# Exploring He Initialization in Deep Neural Networks

## Overview
This project explores the effects of He initialization on the training dynamics of deep neural networks. He initialization is specifically designed for layers with ReLU activation functions, aiming to maintain activation variances throughout the network. This is crucial for efficient training, especially in deep architectures. The project evaluates He initialization's impact on training stability, speed of convergence, and final model performance, using both standard ReLU and PReLU activation functions.

## Tech Stack
- **Programming Languages**: Python
- **Libraries and Frameworks**: PyTorch, NumPy, Matplotlib
- **Datasets**: CIFAR-10

## Challenges Faced
The most difficult aspect of the project was implementing a consistent evaluation framework to compare different configurations of activation functions and weight initialization methods. Addressing this required creating modular functions for data loading, model building, and training. Extensive debugging ensured reproducibility of results across experiments.

## Key Features
1. Comparative analysis of He initialization and standard normal initialization.
2. Evaluation of ReLU and PReLU activation functions.
3. Visualization of weight evolution, convergence speed, and test accuracies.

