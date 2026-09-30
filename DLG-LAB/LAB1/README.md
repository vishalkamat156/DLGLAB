# Deep Learning Lab 1: XOR with MLPs

This lab demonstrates how a multilayer perceptron (MLP) can learn the XOR function, which is not linearly separable. It includes two implementations in `lab1.py`:

1. A small neural network implemented with NumPy, including forward propagation, backpropagation, and weight updates.
2. A Keras model using TensorFlow, with a ReLU hidden layer and sigmoid output layer.

Both implementations use the XOR truth table:

| Input | Output |
| --- | ---: |
| `[0, 0]` | 0 |
| `[0, 1]` | 1 |
| `[1, 0]` | 1 |
| `[1, 1]` | 0 |

## Requirements

- Python 3
- NumPy
- TensorFlow (includes Keras)

Install the packages with:

```bash
python -m pip install numpy tensorflow
```

## Run

```bash
python lab1.py
```

The script prints the NumPy network's predicted values, then evaluates the Keras model and prints its accuracy and rounded predictions. Since the weights are randomly initialized, exact values may vary between runs.
