# 🖼️ Image Classification on Caltech-101 Dataset

This project explores **Image Classification** using the [Caltech-101 dataset](http://www.vision.caltech.edu/Image_Datasets/Caltech101/).  
I started with a **CNN built from scratch** and then boosted performance using **Transfer Learning** with state-of-the-art architectures like **ResNet18** and **EfficientNet-B0**.

---

## 📌 Project Overview
- Implemented a custom **Convolutional Neural Network (CNN)** in PyTorch.  
- Applied **data augmentation** (resize, rotation, horizontal flip, normalization).  
- Improved performance using **Transfer Learning**:
  - **ResNet18**
  - **EfficientNet-B0**

---

## 📂 Dataset
- **Caltech-101** contains **9144 images** across **102 categories**.  
- Images were resized to **128x128** and split:
  - **80% Training**
  - **20% Testing**

---

## 🛠️ Tech Stack
- **Python**
- **PyTorch**
- **Torchvision**
- **Matplotlib / Numpy**

---

## 🚀 Model Performance
| Model              | Test Accuracy |
|--------------------|---------------|
| Custom CNN         | **56.48%**    |
| ResNet18           | **74.58%**    |
| EfficientNet-B0    | **86.33%**    |

---

## 📊 Key Learnings
- Building CNNs from scratch helps in understanding model internals.  
- **Transfer Learning** significantly boosts performance on complex datasets.  
- Pre-trained models like EfficientNet can generalize well with minimal fine-tuning.  

---

🔮 Future Work

- Experiment with other EfficientNet variants (B1–B7).
- Use learning rate schedulers for better convergence.
- Explore Grad-CAM for interpretability.

---



