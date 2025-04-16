# Digits-Classifier-with-PyTorch

## 📋 Project Summary

As a Machine Learning Engineer, you’ve been asked to prototype an Optical Character Recognition (OCR) system to recognize handwritten digits. This project serves as a **proof of concept** using the **MNIST** dataset, a widely-used benchmark dataset for handwritten digit classification.

The project walks through the complete machine learning pipeline:
- Loading and exploring data
- Preprocessing and normalizing images
- Building and training a neural network with PyTorch
- Tuning hyperparameters for improved accuracy
- Evaluating performance on unseen test data
- Saving the trained model for future use

> **Note**: All code and written responses are contained in a single Jupyter Notebook file provided with this repository.

---

## 🚀 Project Goals

- 🔢 Build a neural network capable of classifying digits (0–9) from MNIST images.
- 🧼 Preprocess raw data into tensors for training with PyTorch.
- 🧠 Design and train a deep learning model using PyTorch’s `nn.Module`.
- 🎯 Achieve at least **90% accuracy** on the test set.
- 💾 Save the trained model with `torch.save()` for later use.

---

## 🧰 Tools and Technologies

- Python 3.x
- [PyTorch](https://pytorch.org/)
- torchvision
- Matplotlib (for visualizations)
- Jupyter Notebook

---

## 📁 Repository Structure

```bash
.
├── Digit_Classifier_PyTorch.ipynb   # Jupyter Notebook containing code and explanations
├── README.md                        # This file
└── saved_model.pth                 # Trained PyTorch model (saved after training)
