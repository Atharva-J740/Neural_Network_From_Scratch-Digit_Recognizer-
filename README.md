# Neural Network From Scratch 

This project implements a fully connected neural network from scratch using only **NumPy** for handwritten digit classification on the **MNIST (Kaggle Digit Recognizer)** dataset.

The implementation avoids deep learning frameworks such as TensorFlow and PyTorch to demonstrate the underlying mathematics and mechanics of neural networks.

## Features

- Forward Propagation
- Backpropagation
- Gradient Descent
- ReLU Activation
- Softmax Output Layer
- Cross-Entropy Loss
- One-Hot Encoding
- He Weight Initialization
- Manual Parameter Updates
- Input Normalization
- NumPy Vectorization

## Model Architecture

```
Input (784)
      │
      ▼
Hidden Layer (64 neurons, ReLU)
      │
      ▼
Output Layer (10 neurons, Softmax)
```

## Dataset

- Kaggle Digit Recognizer (MNIST)

## Results

- Initial Accuracy: **~10–11%**
- Final Training Accuracy: **~88–89%**

## Key Learning Outcomes

- Implemented every component of a neural network from scratch
- Debugged matrix dimension, broadcasting, and numerical stability issues
- Applied He Initialization and input normalization to improve convergence
- Gained practical understanding of forward propagation, backpropagation, and gradient descent
