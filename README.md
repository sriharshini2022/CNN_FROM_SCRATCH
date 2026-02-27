<div align="center">

# 🧠 CNN From Scratch  
### 🚀 CIFAR-10 Image Classification | Deep Learning Portfolio Project  

<img src="https://img.shields.io/badge/PyTorch-Framework-red?style=for-the-badge&logo=pytorch">
<img src="https://img.shields.io/badge/Dataset-CIFAR10-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/Model-CNN-green?style=for-the-badge">
<img src="https://img.shields.io/badge/Visualization-Advanced-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/Status-Production Ready-success?style=for-the-badge">

---

🎯 End-to-End CNN Implementation  
📊 Training • Evaluation • Interpretability • Visualization  
💡 Built to deeply understand Convolutional Neural Networks  

</div>

---

# 🌟 Project Overview

This project implements a **Convolutional Neural Network (CNN)** completely from scratch using **PyTorch** to classify images from the CIFAR-10 dataset.

Unlike basic implementations, this project goes beyond training — it focuses on:

- ✅ Model Architecture Design  
- ✅ Custom Training Loop  
- ✅ Performance Analysis  
- ✅ Visualization & Debugging  
- ✅ Model Explainability Techniques  

---

# 🖼️ Dataset – CIFAR-10

| Feature | Details |
|----------|----------|
| Images | 60,000 RGB Images |
| Resolution | 32 × 32 |
| Classes | 10 |
| Train/Test Split | 50,000 / 10,000 |

### 🏷 Classes

Airplane ✈ • Automobile 🚗 • Bird 🐦 • Cat 🐱 • Deer 🦌  
Dog 🐶 • Frog 🐸 • Horse 🐴 • Ship 🚢 • Truck 🚚  

---

# 🏗️ Model Architecture

```
Input (32x32x3)
        ↓
Conv2D → ReLU
        ↓
Conv2D → ReLU
        ↓
MaxPooling
        ↓
Conv2D (64 Filters)
        ↓
MaxPooling
        ↓
Flatten
        ↓
Fully Connected Layer
        ↓
Output Layer (10 Classes)
```

### ⚙️ Training Configuration

| Parameter | Value |
|------------|--------|
| Loss Function | CrossEntropyLoss |
| Optimizer | SGD |
| Learning Rate | 0.001 |
| Momentum | 0.9 |
| Weight Decay | 0.005 |
| Batch Size | 64 |

---

# 📊 Model Performance

### 🔢 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

# 📸 Project Screenshots

> Replace the image paths below with your own screenshots stored in a `/screenshots` folder.

## 🔹 Training Progress

![Training Curve](screenshots/training_curve.png)

## 🔹 Confusion Matrix

![Confusion Matrix](screenshots/confusion_matrix.png)

## 🔹 Feature Map Visualization

![Feature Maps](screenshots/feature_maps.png)

## 🔹 Saliency Map

![Saliency Map](screenshots/saliency_map.png)

---

# 🎥 Demo GIF (Optional but Recommended)

> Add a screen recording GIF of your notebook or visualization output.

```
screenshots/demo.gif
```

```markdown
![Project Demo](screenshots/demo.gif)
```

---

# 🔍 Advanced Visualization & Explainability

This project includes professional-level interpretability techniques:

### 🔥 Saliency Maps  
Highlight which pixels influenced the model’s decision.

### 🎯 Class Activation Mapping (CAM)  
Visual explanation of model attention regions.

### 🗺️ Feature Map Visualization  
Understand convolution layer outputs.

### 🌌 Deep Dream  
Visualizes learned filter patterns.

### 🧬 t-SNE Embedding Visualization  
Projects high-dimensional features into 2D space.

---

# 📂 Output Files

| File | Description |
|------|-------------|
| `best_cnn_cifar10.pth` | Trained model weights |
| `cifar10_results.csv` | Evaluation metrics |
| `cnn_architecture.png` | Model graph visualization |

---

# 🛠️ Tech Stack

- 🐍 Python  
- 🔥 PyTorch  
- 📦 Torchvision  
- 📊 Scikit-Learn  
- 📈 Matplotlib  
- 🎨 Seaborn  
- 🧩 Torchviz  

---

# ⚙️ Installation

```bash
pip install torch torchvision
pip install torchmetrics scikit-learn seaborn
pip install torchviz graphviz
```

---

# 🏋️ Training Workflow

1️⃣ Load & Normalize CIFAR-10  
2️⃣ Build CNN Architecture  
3️⃣ Train with Mini-Batch SGD  
4️⃣ Evaluate on Test Dataset  
5️⃣ Visualize & Interpret Results  

---

# 🎯 Key Learning Outcomes

- Deep understanding of CNN internals  
- Hands-on experience with training pipelines  
- Implementation of evaluation metrics  
- Applying interpretability techniques  
- Visualization-driven model debugging  

---

# 🚀 Future Improvements

- Add Batch Normalization  
- Add Dropout Regularization  
- Learning Rate Scheduler  
- Data Augmentation  
- Implement Residual Connections (ResNet-style)  

---

<div align="center">

## ⭐ If you found this impressive, consider starring the repository!

### 💼 Built as a Deep Learning Portfolio Project  

</div>
