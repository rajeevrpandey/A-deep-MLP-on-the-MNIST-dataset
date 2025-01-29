# 🖥️ Handwritten Digit Classification with Fully Connected Neural Network (FNN)

This project implements a **Fully Connected Neural Network (FNN)** using **TensorFlow & Keras** to classify handwritten digits (0-9) from the **MNIST dataset**. The model is optimized with **EarlyStopping, ModelCheckpoint, and TensorBoard** for efficient training and evaluation.

---

## 📌 Project Overview
✅ Developed an FNN-based digit classifier using the **MNIST dataset**.  
✅ Implemented **EarlyStopping** to prevent overfitting.  
✅ Used **ModelCheckpoint** to save the best-performing model automatically.  
✅ Integrated **TensorBoard** for real-time training visualization.  
✅ Achieved **97-98% accuracy** on test data.  
✅ Trained model is **saved and reloaded** for deployment.

---

## 🚀 Model Architecture
The neural network consists of **three dense layers**:
- **Input Layer:** `Flatten(28x28 → 784)`  
- **Hidden Layers:**
  - Dense (300 neurons, **ReLU** activation)  
  - Dense (100 neurons, **ReLU** activation)  
- **Output Layer:** Dense (10 neurons, **Softmax** activation for multi-class classification)

---

## 📂 Dataset
The project uses the **MNIST dataset** from `tensorflow.keras.datasets.mnist`, which consists of:
- **60,000** training images  
- **10,000** test images  
- Images are **28x28 grayscale** handwritten digits (0-9).  
