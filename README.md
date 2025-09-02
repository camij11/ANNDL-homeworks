# Artificial Neural Networks and Deep Learning Homeworks – Politecnico di Milano

This repository contains the final notebooks and reports for the **Artificial Neural Networks and Deep Learning (AN2DL)** course at Politecnico di Milano.  
The two projects cover **image classification** and **semantic segmentation**, combining deep learning architectures, training strategies, and extensive experimentation.

---

## 📂 Projects

### HW1 – Blood Cell Image Classification
- **Task:** Multiclass classification of blood cell images (8 classes, 96×96 RGB).  
- **Approach:** Progressive experimentation from simple CNNs to transfer learning with EfficientNetB4.  
- **Techniques:** Data cleaning (outliers removal), advanced augmentation (RandAugment, RandMix), layer freezing/unfreezing, optimizer tuning (Adam → Lion).  
- **Results:** Final EfficientNetB4 with fine-tuning and advanced augmentation achieved **92% accuracy** locally and **99.3% accuracy** on validation.  
- **Artifacts:**
  - Report: [`reports/hw1_report.pdf`](reports/hw1_report.pdf)  
  - Notebook: [`notebooks/hw1_classification.ipynb`](notebooks/hw1_classification.ipynb)

---

### HW2 – Semantic Segmentation of Martian Terrain
- **Task:** Pixel-wise classification of 64×128 grayscale Mars images into 5 classes (background, soil, bedrock, sand, big rocks).  
- **Approach:** U-Net based architectures, including a custom dual-branch design with residual connections and squeeze-and-excitation blocks.  
- **Techniques:** Preprocessing (normalization, augmentation), weighted Dice + Focal loss, early stopping, learning-rate scheduling, qualitative visualization callbacks.  
- **Results:** Final dual-branch U-Net achieved **70.24% mean IoU** on validation.  
- **Artifacts:**
  - Report: [`reports/hw2_report.pdf`](reports/hw2_report.pdf)  
  - Notebook: [`notebooks/hw2_segmentation.ipynb`](notebooks/hw2_segmentation.ipynb)
