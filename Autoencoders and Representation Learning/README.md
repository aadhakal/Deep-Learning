# Project 4: Autoencoders and Representation Learning

This project implements and explores autoencoders for dimensionality reduction and representation learning. The goal is to understand how autoencoders compress information into lower-dimensional latent spaces and reconstruct the original data through experimentation and analysis.

---

## Overview

Implemented from scratch using PyTorch, this project includes:

- Basic autoencoder architecture with configurable latent dimensions
- Experiments with different latent space sizes (2, 8, 32, 64)
- Training and evaluation on the MNIST handwritten digit dataset
- Visualization and analysis of reconstructed images

All results are supported by **plots**, **discussion**, and **analysis** included in the accompanying notebook or report.

---

## 📚 Part 1: Basic Autoencoder

### ✅ Implemented:
- Fully-connected autoencoder architecture with encoder and decoder components
- Linear bottleneck with variable latent dimensions
- Training loop with MSE loss and Adam optimizer
- Evaluation of reconstruction quality across different latent dimensions

### 📊 Results:
- Comparison of reconstruction quality across different latent space sizes (2, 8, 32, 64)
- Visualization of original vs. reconstructed images
- Analysis of how latent dimension size affects reconstruction fidelity
- Quantitative evaluation using Mean Squared Error (MSE)

---

## 🔁 Part 2: Latent Space Analysis

### ✅ Implemented:
- Experiments with varying latent dimensions to study information compression
- Evaluation of the trade-off between latent space size and reconstruction quality
- Visualization of reconstructed images for qualitative assessment
- Comparison of test set performance across different model configurations

### 📊 Results:
- Demonstration of how increasing latent dimensions improves reconstruction quality
- Visualization showing the progressive improvement in reconstruction fidelity
- Analysis of the relationship between latent space size and reconstruction error
- Discussion on the minimum latent dimensions needed for acceptable reconstructions

---

## 🔍 Dataset

**MNIST Handwritten Digits**  
Used for training and evaluating autoencoder models on the task of image reconstruction.

---