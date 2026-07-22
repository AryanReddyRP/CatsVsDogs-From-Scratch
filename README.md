# 🐱🐶 Cats vs Dogs Image Classification using CNN from Scratch

A deep learning project that classifies images of cats and dogs using a **Convolutional Neural Network (CNN)** built entirely from scratch with TensorFlow and Keras. The model is trained without transfer learning, learning hierarchical image features directly from the dataset.

---

## 📌 Project Overview

This project implements a custom CNN architecture for binary image classification. The model incorporates modern deep learning techniques such as **Batch Normalization**, **Dropout**, **L2 Regularization**, and **Data Augmentation** to improve generalization and reduce overfitting.

---

## 🚀 Features

- Custom CNN architecture built from scratch
- Image preprocessing and normalization
- Data augmentation (Flip, Rotation, Translation, Zoom)
- Batch Normalization for stable training
- Dropout and L2 Regularization to reduce overfitting
- Early Stopping and Model Checkpointing
- Binary classification (Cats vs Dogs)
- Model evaluation on unseen test images
- Single-image prediction support

---

## 🛠️ Tech Stack

- Python
- TensorFlow & Keras
- NumPy
- Matplotlib
- Kaggle API

---

## 📂 Dataset

- **Dataset:** Dogs vs Cats
- **Image Size:** 256 × 256 pixels
- **Training/Validation Split:** 80% / 20%

---

## 🧠 Model Architecture

- Input Layer (256 × 256 × 3)
- Data Augmentation
- Convolution + ReLU
- Batch Normalization
- Max Pooling
- Dropout
- Multiple CNN blocks with increasing filters
- Flatten Layer
- Fully Connected Dense Layers
- Sigmoid Output Layer

---

## 🔄 Workflow

1. Load and preprocess the dataset.
2. Apply data augmentation.
3. Build a CNN model from scratch.
4. Train using Early Stopping and Model Checkpointing.
5. Evaluate on the test dataset.
6. Predict the class of unseen images.

---

## 📊 Model Evaluation

The model is evaluated using:

- Accuracy
- Binary Cross-Entropy Loss
- Training & Validation Curves

---

## 📁 Repository Structure

```
├── cnn-01.ipynb
├── model.keras
├── README.md
└── images/ (optional)
```

---

## ▶️ How to Run

1. Clone the repository.
2. Install the required dependencies.
3. Download the dataset using the Kaggle API.
4. Run the notebook.
5. Train the model and evaluate its performance.
6. Test the model on new images.

---

## 📈 Future Improvements

- Hyperparameter tuning
- Experiment with deeper CNN architectures
- Compare with Transfer Learning models (VGG16, ResNet50, EfficientNet)
- Deploy as a Streamlit or Flask web application

---

## 👨‍💻 Author

**Aryan Reddy**

If you found this project helpful, consider giving the repository a ⭐.
