# MRI-Images-Segmentation-and-Classification

This repository contains a Jupyter notebook that focuses on Brain MRI image analysis using Deep Learning. It combines two tasks:

1-Segmentation of brain tumors from MRI scans.

2-Classification of brain MRI images (tumor / no-tumor).

# 📌 Project Overview

Medical imaging plays a vital role in diagnosing brain tumors.
The goal of this project is to:

  Automatically segment tumor regions in MRI scans.
  
  Automatically classify MRI scans based on the presence of tumors.
The model is trained on the LGG-MRI Segmentation dataset on kaggle:https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation

# Model Architectures

## 🔹 U-Net (Segmentation)

-Encoder (Contracting path) → extracts deep features.

-Bottleneck → compressed representation.

-Decoder (Expanding path) → reconstructs segmentation mask.

-Skip Connections → help recover fine details (like tumor boundaries).

-Output: Binary mask (tumor = 1, background = 0).

# 🔹 Pretrained ResNet50 (Classification)
Input: Brain MRI image.
Output: Tumor / No-tumor (binary classification).

Plots of Segmentation

![TUMOR](https://github.com/user-attachments/assets/738e77ee-85c4-4edf-a42c-71287947e885)

![TUMOR2](https://github.com/user-attachments/assets/58b841b6-81bd-4e00-9e36-5efdf28321d7)
