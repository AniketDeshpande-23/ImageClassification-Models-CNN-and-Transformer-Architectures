# Image Classification Models — CNN and Transformer Architectures
![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Framework-red)
![Computer Vision](https://img.shields.io/badge/Domain-Computer%20Vision-success)
![Transformers](https://img.shields.io/badge/Models-CNN%20%7C%20ViT%20%7C%20Swin-blueviolet)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

This repository contains implementations of modern deep learning architectures for image classification using PyTorch. It includes both convolutional neural networks and transformer-based vision models, demonstrating transfer learning, training workflows, and performance evaluation on benchmark datasets.

---

## Overview

The project explores the evolution of computer vision models from traditional CNNs to state-of-the-art transformer architectures. Each model is implemented in a separate Jupyter notebook for clarity and reproducibility.

The repository serves as a practical reference for training, fine-tuning, and evaluating image classification models using modern deep learning techniques.

---

## Implemented Models

- Convolutional Neural Network (CNN) — baseline architecture  
- ConvNeXt  
- ConvNeXt V2  
- Vision Transformer (ViT)  
- Swin Transformer  

All models utilize transfer learning with pretrained weights and are adapted for classification tasks.

---

## Methodology

Key components of the training pipeline include:

- Data preprocessing and normalization  
- Data augmentation techniques  
- Transfer learning with pretrained models  
- Fine-tuning for target datasets  
- Performance evaluation using accuracy metrics  
- Visualization of training dynamics  

---

## Project Structure

```
Data-Mining/
│
├── CNN.ipynb
├── ConvNeXt.ipynb
├── ConvNeXt V2.ipynb
├── Vision Transformer.ipynb
├── Swin Transformer.ipynb
└── README.md
```

---

## Requirements

Install dependencies:

```bash
pip install torch torchvision timm matplotlib numpy
```

---

## Usage

Run the notebooks using Jupyter:

```bash
jupyter notebook
```

Open any model notebook and execute the cells sequentially to reproduce training and evaluation results.

---

## Applications

These models are applicable to a wide range of computer vision tasks, including:

- Object classification  
- Industrial inspection  
- Medical imaging  
- Autonomous systems  
- Image understanding applications  

---

## Technology Stack

- Python  
- PyTorch  
- Torchvision  
- TIMM (PyTorch Image Models)  
- NumPy  
- Matplotlib  

---

## Note

This repository is intended for educational and experimental purposes, demonstrating modern deep learning approaches for image classification.
