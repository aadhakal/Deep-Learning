# Deep-Learning
This is my journey to deep learning from scratch


# Project 1: Modern Recurrent Neural Networks

This project explores and implements various modern Recurrent Neural Network (RNN) [The Time Machine](https://www.kaggle.com/datasets/alincijov/time-machine) dataset. The goal of this project is to gain a deep understanding of RNN behavior and improvements through experimentation and ablation studies.

---

## 🚀 Overview

Implemented from scratch using PyTorch, this project includes:

- Basic RNN model with hyperparameter tuning
- Training stability improvements through gradient clipping and activation function exploration
- GRU (Gated Recurrent Unit) implementation and evaluation
- Ablation studies to analyze the role of GRU gates

All results are supported by **plots**, **discussion**, and **analysis** included in the accompanying notebook or report.

---

## 📚 Part 1: Basic RNNs

### ✅ Implemented:
- RNN architecture with manual training loop
- Tokenization and batching for sequential data
- Hyperparameter tuning: hidden units, time steps, learning rate, epochs
- Gradient clipping exploration
- Activation function experiment with ReLU

### 📊 Results:
- Perplexity trends for 3+ top-performing configurations
- Plots comparing training/validation perplexity
- Discussion on the effect of gradient clipping and ReLU

---

## 🔁 Part 2: GRU (Gated Recurrent Unit)

### ✅ Implemented:
- GRU-based language model
- Hyperparameter tuning for performance and training efficiency
- Ablation study: evaluating reset-only and update-only configurations

### 📊 Results:
- Plots for training/validation perplexity across experiments
- Output sequence samples for ablation variants
- Discussion on impact of individual gates on performance

---

## 🔍 Dataset

**[The Time Machine](https://www.kaggle.com/datasets/alincijov/time-machine)** by H.G. Wells  
Used for sequence modeling and next-character prediction tasks.

---

