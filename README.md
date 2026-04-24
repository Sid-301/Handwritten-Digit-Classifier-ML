# Handwritten-Digit-Classifier-ML

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
   git clone [https://github.com/Sid-301/Handwritten-Digit-Classifier-ML.git](https://github.com/Sid-301/Handwritten-Digit-Classifier-ML.git)

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   

   
# Handwritten Digit Classifier using Deep Learning

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow%20%2F%20Keras-orange.svg)
![Accuracy](https://img.shields.io/badge/Accuracy-96.98%25-green.svg)

A high-performance deep learning project that classifies handwritten digits (0-9) from an MNIST-style dataset. This implementation utilizes a Multi-Layer Perceptron (MLP) architecture built with **TensorFlow** and **Keras** to achieve robust predictive accuracy.

## 📊 Project Performance
The model was trained for 10 epochs, resulting in a consistent convergence between training and validation accuracy.

* **Final Validation Accuracy:** 96.98%
* **Final Loss:** 0.1244

### Training Progress
Below is the accuracy curve showing the model's learning trajectory over 10 epochs.

![Validation Accuracy](.Handwritten-Digit-Classifier-ML/images/Validation_accuracy.jpg)

---

## 🧠 Model Architecture
The neural network is designed as a feedforward sequential model:

1. **Input Layer:** `Flatten` layer to convert the 28x28 pixel matrix into a 784-dimensional vector.
2. **Hidden Layer 1:** 128 neurons with `ReLU` activation for non-linear feature mapping.
3. **Hidden Layer 2:** 64 neurons with `ReLU` activation.
4. **Output Layer:** 10 neurons with `Softmax` activation to output class probabilities for digits 0-9.

---

## 🚀 Sample Predictions
The following samples demonstrate the model's ability to correctly identify digits from the test set:

| Sample Image | Model Prediction |
| :---: | :---: |
| ![Result 1](.Handwritten-Digit-Classifier-ML/images/Result_1.jpg) | **Predicted: 9** |
| ![Result 2](.Handwritten-Digit-Classifier-ML/images/Result_2.jpg) | **Predicted: 1** |
| ![Result 3](.Handwritten-Digit-Classifier-ML/images/Result_3.jpg) | **Predicted: 7** |
| ![Result 4](.Handwritten-Digit-Classifier-ML/images/Result_4.jpg) | **Predicted: 1** |
| ![Result 5](.Handwritten-Digit-Classifier-ML/images/Result_5.jpg) | **Predicted: 3** |

---

## 📂 Repository Structure
```text
.
├── dataset/                # Dataset files (train.csv / test.csv)
├── images/                 # Result screenshots and plots
├── notebooks/              # Jupyter notebooks
├── requirements.txt        # Python dependencies
└── README.md
