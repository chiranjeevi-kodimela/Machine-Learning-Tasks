# 🧠 CNN Image Classification using TensorFlow

## ✅ Objective

To build a **Convolutional Neural Network (CNN)** for binary **image classification** using **TensorFlow**, trained on a **synthetic dataset** of colored images (Red vs Blue).

---

## 🔍 Problem Statement

Given a set of colored images (red or blue), the goal is to train a CNN model that can learn to distinguish between them and accurately classify unseen test images.

---

## 🧠 Methodology

We use a **custom-built CNN** that:
- Learns spatial patterns and color features from input images
- Utilizes **convolutional** and **pooling** layers to extract features
- Uses **dense layers** for final binary classification

---

## 📦 Dataset: Synthetic RGB Image Data

- Dataset of **30 images**, each of shape `64x64x3`
- Two classes:
  - Class `0` → Red-colored images
  - Class `1` → Blue-colored images
- **Generated using NumPy** (no external dataset required)

---

## 🔧 Implementation Steps

1. **Install and Import Required Libraries**
2. **Generate the Dataset Programmatically**
3. **Split the Data (Train-Test: 70-30)**
4. **Build a CNN Model using TensorFlow/Keras**
5. **Train the Model**
6. **Evaluate Model Accuracy on Test Data**
7. **Visualize Accuracy, Predictions, and Confusion Matrix**

---

## 📊 Evaluation Metrics

- **Accuracy** on test dataset
- **Confusion Matrix** for classification visualization
- **Classification Report** with Precision, Recall, and F1-Score
- Accuracy and loss curves across training epochs

---

## 🖼️ Sample Output

- Test Accuracy: ~90%–100% (varies slightly due to synthetic randomness)
- Confusion Matrix shows strong separation between red and blue classes
- Example prediction on test image with output label

---

## ✅ Conclusion

This project demonstrates how CNNs can be applied even to small, synthetic datasets for basic image classification tasks. While simple, the approach can be scaled to real-world datasets like **MNIST**, **CIFAR-10**, or custom image folders with minimal changes.

---

## 🙌 Credits

Developed as part of a submission for CodTech Internship 

Created using Google Colab

---

## ✨ Optional Extensions

- Replace synthetic data with a real image dataset (e.g., from Kaggle)
- Add dropout or batch normalization layers for improved regularization
- Deploy model as a web app using **Streamlit** or **Flask**

---
