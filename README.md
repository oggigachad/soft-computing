# Soft Computing

## Jagran Lakecity University
### Faculty of Science and Technology
### BTech CSE

| Academic Details | Information |
| :--- | :--- |
| **Course** | Soft Computing |
| **Student Name** | *Aakash Sarang* |
| **Enrollment No.** | *2023BTCSE001* |
| **Academic Session** | 2026 – 2027 |

---

## Assignment 1 - Module I: Practical Exercises (Fuzzy Logic and Systems)

This repository contains the practical implementations for the 10 assignments of Module I:

### List of Practicals (Module I)

| # | Notebook Link | Exact Aim | Key Concepts & Formulas |
| :---: | :--- | :--- | :--- |
| **01** | [practical1.ipynb](Module%201/practical1.ipynb) | To create and visualize simple fuzzy sets in Python using membership values. | $\mu_A(x) \in [0, 1]$, Core, Support, $\alpha$-Cut $A_\alpha = \{x \mid \mu_A(x) \ge \alpha\}$ |
| **02** | [practical2.ipynb](Module%201/practical2.ipynb) | To create and plot Triangular, Trapezoidal, and Gaussian membership functions using Python and scikit-fuzzy. | $\text{trimf}(x; a, b, c)$, $\text{trapmf}(x; a, b, c, d)$, $\text{gaussmf}(x; m, \sigma)$ |
| **03** | [practical3.ipynb](Module%201/practical3.ipynb) | To perform basic fuzzy set operations such as Union, Intersection, and Complement using Python. | $\mu_{A \cup B} = \max(\mu_A, \mu_B)$, $\mu_{A \cap B} = \min(\mu_A, \mu_B)$, $\mu_{\overline{A}} = 1 - \mu_A$ |
| **04** | [practical4.ipynb](Module%201/practical4.ipynb) | To create and display a simple fuzzy relation between two fuzzy sets using Python. | Min Cartesian Product $R(x, y) = \min(\mu_A, \mu_B)$, Max-Min Composition $R \circ S$ |
| **05** | [practical5.ipynb](Module%201/practical5.ipynb) | To create fuzzy linguistic variables such as Low, Medium, and High using membership functions in Python. | Linguistic Quintuple $(X, T(X), U, G, M)$, Fuzzification Vector $\mathbf{\mu}(x) = [\mu_{\text{Low}}, \mu_{\text{Med}}, \mu_{\text{High}}]$ |
| **06** | [practical6.ipynb](Module%201/practical6.ipynb) | To create simple Fuzzy IF–THEN rules for making decisions based on given input conditions. | Antecedent evaluation (Min/Max), Firing strength $w_i$, Mamdani clipping, Max aggregation |
| **07** | [practical7.ipynb](Module%201/practical7.ipynb) | To implement a simple Mamdani Fuzzy Inference System using Python and scikit-fuzzy. | `skfuzzy.control` Antecedent, Consequent, Rule Base, Centroid Defuzzification |
| **08** | [practical8.ipynb](Module%201/practical8.ipynb) | To implement a simple Sugeno Fuzzy Inference System using Python. | Zero-Order Sugeno FIS, Crisp singleton consequents, Weighted Average $z^* = \frac{\sum w_i z_i}{\sum w_i}$ |
| **09** | [practical9.ipynb](Module%201/practical9.ipynb) | To apply and compare basic defuzzification methods such as Centroid, Bisector, and Mean of Maximum using Python. | Centroid (COG), Bisector (Equal Area), Mean of Max (MOM), Smallest of Max (SOM), Largest of Max (LOM) |
| **10** | [practical10.ipynb](Module%201/practical10.ipynb) | To design a simple Fuzzy Logic Controller using Python and scikit-fuzzy by combining membership functions, fuzzy rules, fuzzy inference, and defuzzification. | Closed-loop feedback FLC: Error $e$, Rate of Change $\Delta e$, 9-rule matrix, Centroid Defuzzification, Closed-loop dynamics |

---

## Assignment 2 - Module II: Practical Exercises (Neural Networks and Deep Learning)

This repository contains the practical implementations for the 10 assignments of Module II:

### List of Practicals (Module II)

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
- **Fuzzy Logic:** scikit-fuzzy (`skfuzzy`)
- **Deep Learning:** TensorFlow 2.20 / Keras
- **Scientific Computing:** NumPy, Scikit-Learn
- **Plotting:** Matplotlib, Seaborn
