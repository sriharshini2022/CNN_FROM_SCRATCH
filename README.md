# 🧠 CNN From Scratch – CIFAR-10 Image Classification  

A complete **Convolutional Neural Network (CNN)** implementation built from scratch using **PyTorch** to classify images from the CIFAR-10 dataset.  

This project demonstrates the full deep learning pipeline including model building, training, evaluation, visualization, and interpretability techniques.

---

## 🚀 Project Highlights

- Custom CNN architecture built using PyTorch  
- CIFAR-10 dataset preprocessing & normalization  
- Model training using SGD with Momentum  
- Performance evaluation with multiple metrics  
- Confusion matrix & classification report  
- Feature map visualization  
- Saliency Maps & Class Activation Mapping (CAM)  
- t-SNE feature embedding visualization  
- Deep Dream implementation  
- Model architecture visualization using Torchviz  

---

## 📂 Dataset

**CIFAR-10 Dataset**

- 60,000 color images (32×32 pixels)  
- 10 Classes:
  - Airplane  
  - Automobile  
  - Bird  
  - Cat  
  - Deer  
  - Dog  
  - Frog  
  - Horse  
  - Ship  
  - Truck  

Split:
- 50,000 Training Images  
- 10,000 Test Images  

---

## 🏗️ Model Architecture

### Convolutional Layers
- Conv2D → ReLU  
- Conv2D → ReLU  
- MaxPooling  
- Conv2D (64 filters)  
- Additional pooling  

### Fully Connected Layers
- Flatten  
- Linear Layer  
- Output Layer (10 classes)  

### Training Configuration
- **Loss Function:** CrossEntropyLoss  
- **Optimizer:** SGD  
  - Learning Rate: 0.001  
  - Momentum: 0.9  
  - Weight Decay: 0.005  
- Batch Size: 64  

---

## ⚙️ Installation

```bash
pip install torch torchvision
pip install torchmetrics scikit-learn seaborn
pip install torchviz graphviz
```

---

## 🏋️ Training Process

- Images resized to 32×32  
- Normalized using CIFAR-10 mean and standard deviation  
- Mini-batch training  
- Multiple epoch training  
- GPU support enabled (if available)  

---

## 📊 Evaluation Metrics

The model is evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- Per-class Classification Report  

Outputs:
- `best_cnn_cifar10.pth` – Saved trained model  
- `cifar10_results.csv` – Evaluation results  
- `cnn_architecture.png` – Model graph visualization  

---

## 📈 Visualization & Interpretability

### Confusion Matrix
Displays class-wise prediction performance.

### Saliency Maps
Highlights important pixels influencing predictions.

### Feature Map Visualization
Displays intermediate convolution outputs.

### Class Activation Mapping (CAM)
Shows model attention regions.

### Deep Dream
Generates patterns maximizing specific filters.

### t-SNE Visualization
2D projection of learned feature embeddings.

---

## 🛠️ Tech Stack

- Python  
- PyTorch  
- Torchvision  
- Torchmetrics  
- Scikit-Learn  
- Seaborn  
- Matplotlib  
- Torchviz  

---

## 📌 Future Improvements

- Add Batch Normalization  
- Add Dropout  
- Implement Learning Rate Scheduler  
- Data Augmentation  
- Experiment with deeper architectures (ResNet-style blocks)  

---

## 👩‍💻 Author

Developed as a hands-on deep learning project to understand CNN architecture, training pipeline, and model interpretability techniques.

---

# ⭐ If you found this useful, consider starring the repository!
