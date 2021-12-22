# PyTorch

This is a simple tutorial to provide an understanding of what is PyTorch and what it is useful for.

## Introduction

PyTorch is defined as an open source machine learning library for Python, used for applications such as computer vision and natural language processing. It is initially developed by Facebook artificial-intelligence research group, and Uber’s Pyro software for probabilistic programming which is built on it.

Originally developed by Hugh Perkins as a Python wrapper based on Torch framework, PyTorch is very "pythonic", meaning it will feel more natural to use if you are already familiar with Python programming. Although the Python interface is more polished and the primary focus of development, PyTorch also has a C++ interface.

PyTorch redesigns and implements Torch in Python while sharing the same core C libraries for the backend code. PyTorch developers tuned this back-end code to run Python efficiently. They also kept the GPU based hardware acceleration as well as the extensibility features that made Lua-based Torch.

## Features

### Easy Interface
- PyTorch offers easy to use API hence it is considered to be very simple to operate and runs on Python. The code execution in this framework is quite easy.

### Python usage
- This library is considered to be Pythonic (as mentioned earlier) which smoothly integrates with the Python data science stack. Thus, it can leverage all the services and functionalities offered by the Python environment.

## Modules
### Autograd module
- PyTorch uses a method called automatic differentiation. A recorder records what operations have been performed, and then it replays it backward to compute the gradients. This method is especially powerful when building neural networks to save time on one epoch by calculating differentiation of the parameters at the forward pass.

### Optim module
- torch.optim is a module that implements various optimization algorithms used for building neural networks. Most of the commonly used methods are already supported, so there is no need to build them from scratch.

### nn module
- PyTorch autograd makes it easy to define computational graphs and take gradients, but raw autograd can be a bit too low-level for defining complex neural networks. This is where the nn module can help.

## Computational graphs 
- PyTorch provides an excellent platform which offers dynamic computational graphs, which means that a user can make changes during runtime. This is very useful when a developer has no way of telling how much memory is required for creating a neural network model.

- PyTorch is known for having three levels of abstraction as given below

   - Tensor: Imperative n-dimensional array which runs on GPU.

   - Variable: Node in computational graph. This stores data and gradient.

   - Module: Neural network layer which will store state or learnable weights.

## Advantages of PyTorch
The following are the advantages of PyTorch:

- easy to debug and understand the code

- includes many layers as Torch

- provides a lot of loss functions

- can be considered as form of NumPy extension to GPUs

- allows building networks whose structure is dependent on computation itself

## TensorFlow vs. PyTorch

<img src="https://github.com/aceirus/PyTorch/blob/main/pictures/PyTorch.vs.TensorFlow.jpg" width=604 height=523 style="float: left; margin-right: 0px;" />
