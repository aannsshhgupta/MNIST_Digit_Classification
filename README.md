# 🧠 MNIST Handwritten Digit Classification

## 🔍 Project Overview
- Implements a neural network to classify digits from the **MNIST dataset**.
- Dataset contains **70,000 grayscale images** (28×28 pixels) of digits from 0 to 9.
- Built using **TensorFlow/Keras**.

## 🧠 Model Architecture
- Input layer: Flatten (28x28 images to 784-length vector).
- Two hidden layers: **Dense(50, ReLU)** each.
- Output layer: **Dense(10, Sigmoid)** for digit classification.
- Loss Function: `sparse_categorical_crossentropy`
- Optimizer: `Adam`

## ⚙️ Preprocessing
- Normalized pixel values (scaled to [0, 1]).
- Training and testing datasets loaded from `keras.datasets.mnist`.

## 📈 Training Details
- Trained for **10 epochs**.
- Uses accuracy as the evaluation metric.

## ✅ Results
- **Test Accuracy**: `96.79%`
- **Test Loss**: `0.1324`

## 📊 Additional Features
- Visualization of sample digits from the dataset.
- Conversion of model predictions from probabilities to class labels.
- Display of model predictions and evaluation on individual test images.
