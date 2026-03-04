# DL-Scratch 🧠

This repo is my personal learning space where I implement core Deep Learning concepts **from scratch** to understand what’s really happening under the hood.[page:2]

The focus is on:
- Minimizing heavy abstractions and black-box APIs
- Rebuilding key ideas with math, numpy, and simple code
- Experimenting with classic ML/DL tasks (classification, regression, sequence models, CNNs, RNNs, etc.)

---

## Contents

### 1. Fundamentals

- `Perceptron_basics.ipynb`  
  Single-layer perceptron implementation from scratch, decision boundary intuition, and basic classification.

- `Gradient_descent_DL.ipynb`  
  Implementation and comparison of Batch vs Stochastic Gradient Descent for optimizing simple models.

- `Back_Prop_Scratch.ipynb`  
  Step-by-step backpropagation implementation for a small neural network, with manual gradient derivations and checks.

- `L2_Regularisation.ipynb`  
  L2 (weight decay) regularization integrated into neural network training to reduce overfitting.

- `Dropout_Layer.ipynb`  
  Custom Dropout layer implementation and experiments showing its effect on overfitting and training dynamics.

---

### 2. Feedforward Networks & Classic Tasks

- `Digit_classification.ipynb`  
  Neural network for handwritten digit classification (MNIST-like setup), built using custom layers and training loop.

- `Credit_card_churn.ipynb`  
  Binary classification model predicting customer churn from tabular credit card data. Includes preprocessing and evaluation metrics.

- `Admission_Predictor.ipynb`  
  Deep learning model for graduate admission prediction (regression), using common admission features and experimenting with network depth and regularization.

---

### 3. Convolutional Networks

- `CNN_implementation.ipynb`  
  From-scratch CNN implementation (convolution, pooling, fully-connected layers) for digit/image classification. Uses the MNIST dataset and compares performance against a perceptron and a simple ANN.

- `Cat_dog_classification.ipynb`  
  Convolutional model for cat-vs-dog image classification, including basic data loading, augmentation ideas, and training loop in Colab.

---

### 4. Sequence Models (RNNs & LSTMs)

- `Rnn_Implementation.ipynb`  
  RNN implementation with a simple model API, showing how recurrent connections work over time steps and how backpropagation through time (BPTT) is applied.

- `about_antas_lstm.ipynb`  
  LSTM-based experiments exploring lstm for sequence modeling, implemented and tested in Colab.

---

## Tech Stack & Philosophy

- Jupyter Notebooks (primarily Google Colab) for interactive experimentation [page:0]
- Python + numerical operations (e.g., numpy) instead of high-level DL frameworks wherever possible
- Emphasis on:
  - Deriving and coding the math manually
  - Visualizing training behavior (loss curves, accuracy)
  - Comparing different optimization and regularization strategies

---
