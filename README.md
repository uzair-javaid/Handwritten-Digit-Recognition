# Handwritten-Digit-Recognition
## 📖 Project Overview

This project implements a **Handwritten Digit Recognition System** using a **Convolutional Neural Network (CNN)** trained on the **MNIST handwritten digit dataset**.

The objective is to accurately classify handwritten digits (0–9) from grayscale images. The project demonstrates the complete deep learning workflow including data preprocessing, CNN model design, training, evaluation, and prediction on custom images.

The model achieves approximately **99% test accuracy** on the MNIST dataset.

---

## 📌 Features

- Load the MNIST handwritten digit dataset
- Perform image preprocessing and normalization
- Build a CNN architecture using TensorFlow/Keras
- Train the CNN model
- Save the trained model
- Evaluate model performance
- Generate confusion matrix
- Plot training accuracy and loss curves
- Predict custom handwritten digit images
- Modular notebooks for each project stage

---




---

## 🗂 Dataset

**Dataset:** MNIST

- Training Images: **60,000**
- Testing Images: **10,000**
- Image Size: **28 × 28 pixels**
- Color Mode: **Grayscale**
- Classes: **10 (Digits 0–9)**

---

## 🧠 CNN Architecture

The CNN consists of the following layers:

1. Conv2D (32 Filters)
2. MaxPooling2D
3. Conv2D (64 Filters)
4. MaxPooling2D
5. Flatten Layer
6. Dense (128 Neurons)
7. Dropout (0.5)
8. Output Layer (Softmax)

---

## ⚙️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV
- Scikit-learn
- Seaborn
- Jupyter Notebook

---



## ▶️ Running the Project

### Step 1

Run

```
1_Dataset_Loading.ipynb
```

---

### Step 2

Run

```
2_CNN_Model.ipynb
```

---

### Step 3

Run

```
3_Model_Training.ipynb
```

This notebook:

- Trains the CNN model
- Saves the trained model
- Generates accuracy and loss graphs

---

### Step 4

Run

```
4_Model_Evaluation.ipynb
```

This notebook:

- Loads the trained model
- Evaluates test accuracy
- Prints the classification report
- Displays the confusion matrix

---

### Step 5

Run

```
5_Prediction.ipynb
```

This notebook:

- Loads the saved CNN model
- Reads a custom handwritten image
- Predicts the digit
- Displays the confidence score

---

## 📈 Results

The trained CNN model achieves approximately:

| Metric | Value |
|---------|--------|
| Test Accuracy | ~99% |
| Dataset | MNIST |
| Classes | 10 |
| Image Size | 28×28 |

---

## 📊 Visual Results

The repository includes:

- Training Accuracy Curve
- Training Loss Curve
- Confusion Matrix
- Sample Predictions

---

## 🎯 Future Improvements

- Improve robustness for noisy handwritten images
- Develop a web application using Flask or Streamlit
- Train on larger handwritten datasets
- Deploy the model on cloud platforms

---

## 👨‍💻 Author

**Uzair Malik**

B.Tech Computer Science & Engineering

Machine Learning | Deep Learning | Data Science Enthusiast

