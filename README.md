# Generative_AI# 🧠 Basic GAN on MNIST – PyTorch (Google Colab)

This repository contains a simple yet complete implementation of a **Generative Adversarial Network (GAN)** using **PyTorch** to generate handwritten digits similar to the MNIST dataset.

---

## 🔍 Overview

- Uses **fully connected (FC)** neural networks for both Generator and Discriminator.
- Trained on **MNIST** dataset.
- Generates realistic-looking handwritten digits from random noise.
- Optimized for execution on **Google Colab with GPU support**.

---

## 🚀 Getting Started

### ▶️ Run in Google Colab

Click the button below to launch in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

> Make sure to go to `Runtime` → `Change runtime type` → Select `GPU`.

---

## 📁 Files

| File | Description |
|------|-------------|
| `gan_mnist.ipynb` | Full training code for GAN using PyTorch |
| `README.md`       | Project overview and setup instructions  |

---

## 🧠 Key Features

- Generator and Discriminator implemented using `torch.nn.Sequential`
- Binary Cross-Entropy Loss (BCE)
- Adam Optimizer
- Normalized MNIST input for `tanh` output
- Visualization of generated digits every 10 epochs

---

## 🖼️ Sample Output

After ~50 epochs, the model learns to generate digits that resemble real MNIST digits:

*(add screenshots of your generated digits here)*

---

## 📦 Dependencies

- Python ≥ 3.6
- torch ≥ 1.10
- torchvision
- matplotlib

Install with pip:
```bash
pip install torch torchvision matplotlib
