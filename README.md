# Fashion-MNIST Classification using PyTorch

A beginner-friendly Deep Learning project built with PyTorch to classify various clothing and apparel items (such as shirts, shoes, bags, etc.) using the classic **Fashion-MNIST** dataset and an Artificial Neural Network (ANN).

## 🚀 Features
- **Dataset Loading:** Automatically downloads and preprocesses the Fashion-MNIST dataset using PyTorch `DataLoader`.
- **Neural Network Architecture:** Implements a fully connected Feedforward Neural Network (ANN) using `nn.Sequential`.
- **Training Pipeline:** Trains the model using Cross-Entropy Loss and the Adam Optimizer over multiple epochs.
- **Evaluation:** Computes the overall test accuracy of the model.
- **Single Image Prediction & Targeting:** Tests predictions on individual items from the test dataset (including custom category targeting like finding and predicting specific items such as shirts or boots) and visualizes them using Matplotlib.

## 🛠️ Tech Stack
- **Python**
- **PyTorch**
- **Torchvision**
- **Matplotlib**

## 📂 Project Structure
```text
├── fashion_mnist_project.ipynb  
├── fashion_model.pth            
├── requirements.txt             
└── README.md                    
