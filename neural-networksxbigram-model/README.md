# makemoreNeuralNetworks.ipynb

## Overview

This Jupyter notebook is an educational deep dive into building and training neural networks from scratch using PyTorch, inspired by the "makemore" series by Andrej Karpathy. The notebook demonstrates how to construct a character-level language model to generate new names, starting from basic data processing to implementing a multi-layer perceptron (MLP) with batch normalization.

## Features

- **Data Preparation**: Reads a list of names, builds a character vocabulary, and encodes names into integer sequences suitable for neural network input.
- **Dataset Construction**: Splits the data into training, validation, and test sets, and prepares context windows for next-character prediction.
- **MLP Implementation**: 
  - Implements a simple MLP with a single hidden layer, then extends to a deeper network with multiple hidden layers.
  - Introduces custom implementations of linear layers, batch normalization, and activation functions (Tanh).
- **Training Loop**: 
  - Trains the model using stochastic gradient descent, tracks and visualizes loss, and applies learning rate scheduling.
  - Includes detailed statistics and visualizations of activations and gradients to analyze network behavior.
- **Evaluation**: 
  - Evaluates model performance on train, validation, and test splits.
  - Samples new names from the trained model to demonstrate generative capabilities.
- **Educational Widgets**: 
  - Provides interactive widgets and visualizations to illustrate the effects of normalization and network initialization.
- **Advanced Analysis**: 
  - Explores the impact of batch normalization and weight initialization on forward and backward pass statistics.

## How to Use

1. **Dependencies**: Requires Python, PyTorch, matplotlib, numpy, scipy, and ipywidgets.
2. **Data**: Expects a `names.txt` file with one name per line in the working directory.
3. **Run All Cells**: Execute the notebook from top to bottom to reproduce the results and visualizations.
4. **Experiment**: Modify hyperparameters, network depth, or data to explore different behaviors and outcomes.

## Educational Value

This notebook is ideal for learners who want to:
- Understand the inner workings of neural networks and their training dynamics.
- See how batch normalization and initialization affect deep networks.
- Gain hands-on experience with PyTorch and custom layer implementations.
- Explore generative modeling at the character level.

---

**Note:**
- The notebook is complete and ready for use or further experimentation.
- For best results, ensure all dependencies are installed and the required data file is present. 