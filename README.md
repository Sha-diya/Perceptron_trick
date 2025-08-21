# Perceptron Trick – Python Implementation

## 🧠 Overview

This repository contains a Python implementation of the **Perceptron Trick**, a fundamental concept in machine learning.  
The Perceptron algorithm is a **linear classifier** used for binary classification tasks and serves as a building block for more complex neural networks.

---

## 📂 File Structure
Perceptron_trick/  
├── perceptron_trick.py # Core implementation of the Perceptron algorithm  
└── README.md # Project documentation  

---

## 🚀 Usage

To run the Perceptron algorithm:

1. **Clone the repository:**

```bash
git clone https://github.com/Sha-diya/Perceptron_trick.git
cd Perceptron_trick
```
2. **Install dependencies:**

```bash
pip install numpy matplotlib
```

3. **Run the script:**

```bash
python perceptron_trick.py
```

**🔧 Dependencies**
- numpy
- matplotlib

These are used for numerical computation and visualization of the decision boundary.

---


**📘 About the Perceptron Trick**

The Perceptron Trick involves updating the weights of the Perceptron model whenever a misclassification occurs.
This iterative process allows the model to converge towards an optimal decision boundary for linearly separable data.

*Key Steps:*
1. Initialize weights and bias to zero (or small random values).
2. For each training sample:
   - Compute the output using the current weights.
   - Update weights if the prediction is wrong:
     ```bash
     w = w + learning_rate * (y_true - y_pred) * x
     b = b + learning_rate * (y_true - y_pred)
     ```
3. Repeat for multiple epochs until convergence.

**📚 Further Reading**
[Implementing the Perceptron Neural Network with Python](https://pyimagesearch.com/2021/05/06/implementing-the-perceptron-neural-network-with-python/)
[The Perceptron Algorithm from Scratch Using Python](https://www.quarkml.com/2022/12/perceptron-algorithm-understanding-and-implementation-python.html)

**⚡ Features**
- Simple and intuitive binary classifier implementation.
- Uses numpy for vectorized operations.
- Visualizes decision boundary using matplotlib.
