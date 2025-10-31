# 🦴 Bone Fracture Classification using VGG16 + Random Forest  
*Reproducing the best-performing approach from a published research paper*

---

## 📘 Overview

This project implements the **best approach** from the paper:

> **"VGG-16, VGG-16 With Random Forest, ResNet50 With SVM, and EfficientNetB0 With XGBoost: Enhancing Bone Fracture Classification in X-Ray Using Deep Learning Models" (2024)**

Instead of reproducing all experiments and comparisons, this work focuses exclusively on applying the **final and optimal model** identified by the authors, a **VGG16 feature extractor combined with a Random Forest classifier**.  
According to the paper, this approach achieved **the highest classification accuracy (~95%)** on bone fracture X-ray images.

---

## 🎯 Objectives

- Implement and validate the **best-performing model** from the cited study.  
- Build a **reproducible deep learning + ensemble pipeline** for X-ray image classification.  
- Prepare the trained model for deployment .  

---

## ⚙️ Methodology

### 1. Feature Extraction
- Use **VGG16** (pre-trained on ImageNet) without top layers.  
- Apply preprocessing consistent with ImageNet normalization.  
- Extract deep feature vectors for each image.

### 2. Classification
- Train a **RandomForestClassifier** on the extracted features.  
- Evaluate performance using accuracy, precision, recall, F1-score, and confusion matrix.

### 3. Deployment
- Save both trained models for reuse:  


---

## 🧩 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone git@github.com:Baya-Mezghani/Bone-Fracture-Classification.git
cd Bone-Fracture-Classification
```
---
## 📚 Reference

> **S. Torne. Author *et al.***,  
> *“VGG-16, VGG-16 With Random Forest, ResNet50 With SVM, and EfficientNetB0 With XGBoost: Enhancing Bone Fracture Classification in X-Ray Using Deep Learning Models,”*  
> **IEEE Access**, published Jan. 27, 2025.  
> DOI: [10.1109/ACCESS.2025.3534818](https://doi.org/10.1109/ACCESS.2025.3534818)

