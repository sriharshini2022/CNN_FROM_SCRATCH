<div align="center">

# 🧠 CNN From Scratch  
### 🎯 CIFAR-10 Image Classification using PyTorch  

<img src="https://img.shields.io/badge/PyTorch-DeepLearning-red?style=for-the-badge&logo=pytorch">
<img src="https://img.shields.io/badge/Dataset-CIFAR10-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/Model-CNN-green?style=for-the-badge">
<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">

---

🚀 End-to-End Convolutional Neural Network built from scratch  
📊 Training • Evaluation • Visualization • Interpretability  

</div>

---

## 📌 Project Overview

This project implements a **Convolutional Neural Network (CNN)** from scratch using **PyTorch** to classify images from the CIFAR-10 dataset.

It covers:

✔ Model Architecture Design  
✔ Training Pipeline  
✔ Performance Evaluation  
✔ Advanced Visualization Techniques  
✔ Model Interpretability  

---

## 📂 Dataset – CIFAR-10

| Feature | Details |
|---------|----------|
| Total Images | 60,000 |
| Image Size | 32 × 32 RGB |
| Classes | 10 |
| Training Images | 50,000 |
| Test Images | 10,000 |

### 🏷 Classes

Airplane • Automobile • Bird • Cat • Deer • Dog • Frog • Horse • Ship • Truck  

---

## 🏗️ Model Architecture

```
Input Image (32x32x3)
        ↓
Conv2D → ReLU
        ↓
Conv2D → ReLU
        ↓
MaxPooling
        ↓
Conv2D (64 filters)
        ↓
MaxPooling
        ↓
Flatten
        ↓
Fully Connected Layer
        ↓
Output (10 Classes)
```

### ⚙️ Training Configuration

- **Loss Function:** CrossEntropyLoss  
- **Optimizer:** SGD  
  - Learning Rate: 0.001  
  - Momentum: 0.9  
  - Weight Decay: 0.005  
- Batch Size: 64  

---

## 📊 Evaluation Metrics

✔ Accuracy  
✔ Precision  
✔ Recall  
✔ F1-Score  
✔ Confusion Matrix  
✔ Classification Report  

📁 Outputs Generated:

- `best_cnn_cifar10.pth`  
- `cifar10_results.csv`  
- `cnn_architecture.png`  

---

## 🔍 Visualization & Interpretability

This project includes advanced deep learning explainability techniques:

### 🔥 Saliency Maps
Highlight important pixels affecting predictions.

### 🗺 Feature Maps
Visualize intermediate convolutional outputs.

### 🎯 Class Activation Mapping (CAM)
Shows where the model is focusing.

### 🌌 Deep Dream
Enhances patterns learned by filters.

### 🧬 t-SNE Embeddings
2D visualization of learned feature space.

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|--------|
| Language | Python |
| Deep Learning | PyTorch |
| Dataset | Torchvision |
| Metrics | Torchmetrics, Scikit-Learn |
| Visualization | Matplotlib, Seaborn |
| Graph Visualization | Torchviz |

---

## ⚙️ Installation

```bash
pip install torch torchvision
pip install torchmetrics scikit-learn seaborn
pip install torchviz graphviz
```

---

## 🏋️ Training Workflow

1️⃣ Load & Normalize Dataset  
2️⃣ Define CNN Architecture  
3️⃣ Train Model using Mini-Batch SGD  
4️⃣ Evaluate on Test Data  
5️⃣ Visualize Metrics & Interpret Results  

---

## 🎯 Learning Outcomes

- Understanding CNN internals  
- Building custom training loops  
- Implementing evaluation metrics  
- Applying model interpretability techniques  
- Visual debugging using feature maps  

---

## 🚀 Future Improvements

- Add Batch Normalization  
- Add Dropout Regularization  
- Learning Rate Scheduler  
- Data Augmentation  
- Implement ResNet-style architecture  

---

<div align="center">

### ⭐ If you like this project, give it a star!

Built for deep learning practice & academic understanding.

</div>
