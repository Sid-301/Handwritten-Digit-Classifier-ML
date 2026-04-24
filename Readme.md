# Handwritten Digit Detection using Neural Networks

A deep learning project that classifies handwritten digits (0-9) using a Feedforward Neural Network built with **TensorFlow** and **Keras**. This model achieves ~97% accuracy on the MNIST-style dataset.

## 📊 Project Overview
This project demonstrates the full machine learning pipeline:
- **Data Preprocessing:** Normalization, Reshaping, and One-Hot Encoding.
- **Architecture:** A 3-layer Sequential Neural Network.
- **Evaluation:** Accuracy/Loss visualization and real-time prediction testing.

## 🧠 Model Architecture
- **Input Layer:** Flatten (28x28 images to 784 vector)
- **Hidden Layer 1:** 128 Neurons (ReLU activation)
- **Hidden Layer 2:** 64 Neurons (ReLU activation)
- **Output Layer:** 10 Neurons (Softmax activation for multi-class probability)

## 🛠️ Installation
1. Clone the repo:
   ```bash
   git clone [https://github.com/SID-301/Handwritten-Digit-Classifier-ML.git](https://github.com/SID-301/Handwritten-Digit-Classifier-ML.git)