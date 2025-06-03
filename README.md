# 🧠 Handwritten Digit Recognition with Deep Neural Network (DNN)

This project trains and evaluates a fully connected Deep Neural Network (DNN) on the MNIST dataset using TensorFlow and Keras.  

---

## 📌 Project Overview

- **Dataset**: MNIST dataset of handwritten digits (28x28 grayscale images)
- **Objective**: Build and evaluate a DNN to classify digits (0–9)
- **Model**: Sequential model using `Dense`, `ReLU`, and `Softmax` layers
- **Format**: Raw `.npz` file loading and reshaping to 1D input vectors

---

## 🧠 Key Concepts

- Data loading and reshaping using `numpy`
- Manual preprocessing of `.npz` file format
- Construction of a Keras Sequential DNN
- Training with `categorical_crossentropy` loss and `SGD` optimizer
- Visualization of training accuracy and loss

---

## 📁 Files

| File                  | Description                          |
|-----------------------|--------------------------------------|
| `Script DNN MNIST.ipynb` | Main training and evaluation notebook |
| `mnist.npz`           | Input data (must be added manually)  |
| `README.md`           | Project documentation                |

---

## 🚀 How to Run

1. Place `mnist.npz` in the same folder as this notebook
2. Open `Script DNN MNIST.ipynb` in Jupyter or VS Code
3. Run all cells to train and test the neural network

---

## 📈 Output

- Model architecture summary
- Training accuracy and loss visualization
- Final evaluation accuracy on the test set

---

## 🧰 Tools Used

- Python 3.x
- NumPy, Matplotlib
- TensorFlow + Keras
