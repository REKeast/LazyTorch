# PyTorch Neural Network Code Generator (Tkinter GUI)

A graphical interface to design and export custom feedforward neural networks in PyTorch. This tool allows you to build models layer-by-layer, configure training parameters, and generate fully working Python code — including optional training loops with dummy data.

##  Features

-  Add, reorder, and configure hidden layers (size, activation, dropout)
-  Specify input/output dimensions, loss function, optimizer, and training settings
-  Supported activation functions:
  - ReLU
  - Tanh
  - Sigmoid
  - Leaky ReLU
  - GELU
  - Swish (SiLU)
  - None (linear)
-  Automatically generate PyTorch model class
-  Optional training loop with dummy data
-  Save generated code to a `.py` file
-  Copy code to clipboard directly from the interface

##  Interface Overview

- **Model Configuration**: Set the class name, input size, and output size.
- **Training Configuration**: Choose the number of epochs, learning rate, optimizer, and loss function.
- **Layer Builder**: Define each layer's size, activation, and optional dropout.
- **Current Layers**: View and manage the sequence of layers you've added.
- **Generated Code**: View, copy, or save your generated PyTorch code.

##  Requirements

- Python 3.x
- Tkinter (usually included with standard Python installations)
- PyTorch (`pip install torch`)

