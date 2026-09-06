# Soft Computing

## Jagran Lakecity University
### Faculty of Science and Technology
### BTech CSE

| Academic Details | Information |
| :--- | :--- |
| **Course** | Soft Computing |
| **Module** | Module II: Fuzzy Logic and Systems |
| **Student Name** | *Aakash Sarang* |
| **Enrollment No.** | *2023BTCSE001* |
| **Academic Session** | 2026 – 2027 |

---

## Assignment 2 - Module II: Practical Exercises

This repository contains the practical implementations for the 10 assignments of Module II:

### List of Practicals

| # | Notebook Link | Exact Aim | Key Concepts & Formulas |
| :---: | :--- | :--- | :--- |
| **01** | [practical1.ipynb](Module%202/practical1.ipynb) | To understand and implement the basic working of an artificial neuron using Python. | $z = \mathbf{w} \cdot \mathbf{x} + b$, Step function $f(z)$ |
| **02** | [practical2.ipynb](Module%202/practical2.ipynb) | To implement the weighted sum of inputs and bias used in an artificial neuron using Python. | $z = \sum w_i x_i + b$, Matrix batch $Z = X W^T + b$ |
| **03** | [practical3.ipynb](Module%202/practical3.ipynb) | To implement and visualize Sigmoid, Tanh, and ReLU activation functions using Python. | $\sigma(z) = \frac{1}{1+e^{-z}}$, $\tanh(z)$, $\text{ReLU}(z) = \max(0,z)$ |
| **04** | [practical4.ipynb](Module%202/practical4.ipynb) | To create a simple single-layer neural network using Python. | Single-layer network, $\Delta w_i = \eta \cdot e \cdot x_i$ |
| **05** | [practical5.ipynb](Module%202/practical5.ipynb) | To create a Multilayer Perceptron (MLP) with input, hidden, and output layers using Keras/TensorFlow. | Keras Sequential MLP, $\text{Params} = (N_{\text{in}} \times N_{\text{out}}) + N_{\text{out}}$ |
| **06** | [practical6.ipynb](Module%202/practical6.ipynb) | To apply Gradient Descent for updating the weights of a simple neural network during training. | Gradient Descent: $w \leftarrow w - \alpha \frac{\partial \text{MSE}}{\partial w}$ |
| **07** | [practical7.ipynb](Module%202/practical7.ipynb) | To understand and implement the basic concept of Backpropagation for training a neural network. | Backpropagation: Forward pass, Chain rule $\delta_o, \delta_h$, Weight updates |
| **08** | [practical8.ipynb](Module%202/practical8.ipynb) | To train a simple neural network model on a dataset using Keras/TensorFlow. | Keras training, Scaling $x_{\text{scaled}} = \frac{x-\mu}{\sigma}$, Dropout |
| **09** | [practical9.ipynb](Module%202/practical9.ipynb) | To evaluate the performance of a trained neural network using suitable evaluation metrics in Python. | Accuracy, Precision, Recall, Specificity, F1-Score, Confusion Matrix |
| **10** | [practical10.ipynb](Module%202/practical10.ipynb) | To design, train, and evaluate a complete Artificial Neural Network-based classification system using Python and Keras/TensorFlow by integrating input features, hidden layers, activation functions, training, and model evaluation. | Complete integrated pipeline: Features, Hidden layers, Training, Evaluation |

---

### Software & Environment
- **Python:** 3.13
- **Deep Learning:** TensorFlow 2.20 / Keras
- **Scientific Computing:** NumPy, Scikit-Learn
- **Plotting:** Matplotlib, Seaborn
