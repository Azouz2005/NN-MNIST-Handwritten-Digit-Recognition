# MNIST Handwritten Digit Recognition using Neural Networks

This project is a Deep Learning-based Handwritten Digit Recognition system built using PyTorch and a Multi-Layer Perceptron (MLP) Neural Network. The model is trained on the famous MNIST dataset to classify handwritten digits from 0 to 9. The project focuses on building and training a Neural Network from scratch while understanding the full Deep Learning workflow including preprocessing, training, evaluation, and visualization.

The training pipeline includes image normalization and batching using PyTorch DataLoaders to improve training efficiency and model performance. The neural network architecture consists of fully connected layers with ReLU activation functions, while the model is optimized using the Adam optimizer with CrossEntropyLoss.

The project also includes visualization of training and validation accuracy/loss curves, along with prediction visualization showing the true and predicted digit labels. The model achieved high classification accuracy on the MNIST test dataset, demonstrating strong performance in handwritten digit recognition tasks.

The project supports GPU acceleration using CUDA for faster training and can be extended in the future using Convolutional Neural Networks (CNNs), Dropout regularization, model deployment, or real-time digit recognition applications.

---

# Features

- Handwritten Digit Classification (0–9)
- Neural Network implemented using PyTorch
- MNIST Dataset integration
- Training & Validation accuracy/loss visualization
- Prediction visualization with true vs predicted labels
- GPU support using CUDA
- Image preprocessing & normalization
- Adam optimizer with CrossEntropyLoss

---

# Technologies Used

- Python
- PyTorch
- Torchvision
- Matplotlib
- NumPy

---

# Dataset

The project uses the MNIST Handwritten Digit Dataset.

### Dataset Details

- 70,000 grayscale handwritten digit images
- Image size: 28×28
- 10 output classes (Digits 0–9)
- Automatically downloaded using Torchvision

---

# Model Architecture

The project uses:

- Multi-Layer Perceptron (MLP)
- Fully Connected Layers
- ReLU Activation Function
- Adam Optimizer
- CrossEntropyLoss

### Architecture

```text
Input Layer (784)
       ↓
Hidden Layer (128 neurons)
       ↓
Hidden Layer (64 neurons)
       ↓
Output Layer (10 classes)
```

---

# Training Techniques

## Data Preprocessing

The preprocessing pipeline includes:

- Tensor Conversion
- Image Normalization
- DataLoader batching

## Optimization

- Adam Optimizer
- Learning Rate = 0.001
- CrossEntropyLoss

---

# Training Results

- High Training Accuracy achieved
- Strong Test Accuracy on unseen data
- Stable loss reduction during training
- Accuracy/Loss curves visualized during training

---