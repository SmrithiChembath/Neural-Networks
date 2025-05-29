# Neural Network



## Features

- `Linear`, `Sigmoid`, `ReLU`, and `Tanh` layers
- Binary Cross-Entropy loss
- Forward and backward propagation
- Gradient descent with learning rate control
- Model serialization with `pickle`
- Solves the XOR problem successfully

## Problem Statement

Train a neural network to solve the XOR truth table using only NumPy — no PyTorch, TensorFlow, or Keras.

| Input (X) | Output (y) |
|-----------|------------|
| [0, 0]    | 0          |
| [0, 1]    | 1          |
| [1, 0]    | 1          |
| [1, 1]    | 0          |



## Training Flow

1. Define architecture using the custom `Sequential` class
2. Train the model for a number of epochs
3. Track loss and update weights via backpropagation
4. Evaluate on test inputs

