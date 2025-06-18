# MNIST Digit Classification & Data Visualization

This project demonstrates the use of TensorFlow and data visualization techniques to build and evaluate a simple neural network for handwritten digit classification using the MNIST dataset. The project also includes several insightful visualizations to understand the data and model performance.

## 📌 Project Overview

The goal of this project is to:

- Load and preprocess the MNIST dataset.
- Train a simple feedforward neural network for multi-class digit classification.
- Visualize and evaluate model performance using multiple chart types.
- Explore the distribution and prediction behavior of the model using plots and metrics.

---

## 🧠 Neural Network Model

A simple neural network is built using TensorFlow's Sequential API:

- **Input Layer:** Flatten 28x28 images into 784-element vectors.
- **Hidden Layers:** Two dense layers with 256 and 128 neurons using sigmoid activation.
- **Output Layer:** 10 neurons (0–9 classes) with sigmoid activation.

The model is trained using the **Adam optimizer** and **sparse categorical cross-entropy** as the loss function, over **50 epochs** with a **batch size of 2000** and **20% validation split**.

---

## 📊 Visualizations

This project includes multiple visualization techniques to explore both data and model performance:

### 1. Sample Image Grid
- A grid of 100 randomly selected images from the training dataset, showcasing the variety of handwritten digits.

### 2. Confusion Matrix
- A heatmap of the confusion matrix to show the performance of the model across all classes.
- Helps identify which digits the model tends to confuse with others.

### 3. Model Evaluation Line Chart
- A simple line plot showing the loss and accuracy obtained on the test dataset after training.

### 4. Histogram of True Digits
- A histogram showing the frequency of each digit in the test dataset.
- Provides insight into the class balance in the dataset.

### 5. Pie Chart of Predicted Digit Distribution
- Visual representation of how often each digit was predicted by the trained model.
- Useful for spotting class imbalance in predictions.

### 6. Density Plot of Probabilities (Digit '7')
- A KDE (Kernel Density Estimate) plot showing the distribution of prediction probabilities for the digit '7'.
- Helps understand the model's confidence when predicting this particular class.

---

## ✅ Final Evaluation

- The model was evaluated on the test set for both loss and accuracy.
- The confusion matrix and visualization tools help assess areas where the model performs well and where it could be improved.

---

## 📂 Dataset

- The project uses the **MNIST** dataset available from TensorFlow datasets.
- It includes 60,000 training images and 10,000 test images of handwritten digits (0–9), each of size 28x28 pixels.

---

## 🧰 Technologies Used

- **Python**
- **TensorFlow / Keras**
- **Matplotlib**
- **Seaborn**
- **NumPy**
- **scikit-learn**

---

## 📈 Use Case

This project can serve as a beginner-friendly tutorial for:

- Learning basic neural network modeling with TensorFlow.
- Applying data visualization techniques to evaluate classification models.
- Understanding how different plots can inform decisions in a machine learning workflow.
