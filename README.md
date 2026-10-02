# 🪨📄✂️ Rock Paper Scissors Image Classification Using CNN

## 📌 Project Overview

This project uses a **Convolutional Neural Network (CNN)** to classify images into three categories:

- 🪨 Rock
- 📄 Paper
- ✂️ Scissors

The project was developed using **Python, TensorFlow, Keras, NumPy, Matplotlib, and Scikit-learn**.

The main purpose of this project is to understand the complete workflow of an image classification project using Kaggle and deep learning.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand how image datasets are used in deep learning.
- Perform basic image preprocessing.
- Resize and normalize images.
- Apply data augmentation.
- Build a CNN image classification model.
- Train and validate the model.
- Evaluate model performance.
- Generate a confusion matrix.
- Calculate Precision, Recall, and F1-score.
- Test the model on an individual image.

---

## 📂 Dataset

The project uses the **Rock-Paper-Scissors Images** dataset.

### Classes

The dataset contains three classes:

1. Paper
2. Rock
3. Scissors

### Dataset Statistics

| Class | Number of Images |
|---|---:|
| Paper | 712 |
| Rock | 726 |
| Scissors | 750 |
| **Total** | **2,188** |

### Dataset Source

The dataset was obtained from Kaggle.

[Kaggle - Rock-Paper-Scissors Images](https://www.kaggle.com/datasets/drgfreeman/rockpaperscissors)

> The dataset itself is not included in this GitHub repository.

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- PIL
- Kaggle

---

## 🧠 Model Architecture

A basic Convolutional Neural Network was developed using the following layers:

```text
Input Image
     ↓
Data Augmentation
     ↓
Conv2D (32 filters)
     ↓
MaxPooling2D
     ↓
Conv2D (64 filters)
     ↓
MaxPooling2D
     ↓
Conv2D (128 filters)
     ↓
MaxPooling2D
     ↓
Flatten
     ↓
Dense (128 neurons)
     ↓
Dropout (0.5)
     ↓
Dense (3 neurons)
     ↓
Softmax
     ↓
Prediction
