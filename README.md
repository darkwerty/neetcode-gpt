# neetcode-gpt

Neural network building blocks written from scratch in NumPy and PyTorch, from my solutions to the NeetCode
machine learning course. The goal is to end with a small GPT assembled from these pieces. **Work in progress:**
so far it covers the foundations and the normalization layers; attention and the transformer are not here yet.

## What's here

### `foundations/`

| File | What it does |
|---|---|
| `neuron.py` | Forward pass of a single neuron with sigmoid or ReLU |
| `backprop.py` | Gradients of a single neuron by hand |
| `mlp.py` | Forward pass of a multi-layer perceptron |
| `multi_layer_backprop.py` | Forward and backward pass through several layers |
| `linear_regression_training.py` | Linear regression trained with gradient descent |
| `training_loop.py` | A full training loop in NumPy |
| `weight_init.py` | Xavier and Kaiming initialization, and how activations behave across layers with each |
| `training_diagnostics.py` | Activation and gradient statistics per layer to spot vanishing or exploding gradients |
| `pytorch_basics.py` | Reshape, mean, concatenation and loss with PyTorch tensors |
| `digit_classifier.py` | A small PyTorch network for MNIST digits (784 inputs, 10 classes, dropout) |

### `model/`

| File | What it does |
|---|---|
| `normalization.py` | Layer normalization |
| `batch_normalization.py` | Batch normalization |
| `rms_normalization.py` | RMS normalization |

Each file is a `Solution` class, the format the course uses to check the answers.
