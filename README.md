# 🧠 GAN Variants Collection (DCGAN / LSGAN / WGAN / WGAN-GP)

This repository implements and compares four foundational variants of Generative Adversarial Networks (GANs) using PyTorch. It aims to provide a clean, modular, and reproducible platform for studying how different GAN training strategies affect image generation quality and model stability.

---

## 🎯 Project Purpose

Generative Adversarial Networks are notoriously difficult to train. This project was built to answer one central question:

> **"How do different GAN formulations affect the convergence and visual output quality?"**

By implementing four models from scratch—DCGAN, LSGAN, WGAN, and WGAN-GP—and running them under consistent experimental settings, this work offers both a technical and educational perspective into adversarial learning.

---

## 📘 Implemented Models

| Model       | Core Idea                                  | Stability | Paper Reference            |
|-------------|---------------------------------------------|-----------|----------------------------|
| **DCGAN**   | Convolutional GAN with ReLU/Tanh            | ⭐⭐        | Radford et al. (2015)      |
| **LSGAN**   | Least Squares Loss replaces BCE             | ⭐⭐        | Mao et al. (2017)          |
| **WGAN**    | Wasserstein Loss + Weight Clipping          | ⭐⭐⭐       | Arjovsky et al. (2017)     |
| **WGAN-GP** | Gradient Penalty to enforce Lipschitz constraint | ⭐⭐⭐⭐  | Gulrajani et al. (2017)    |

---

## 🧠 Skills & Tech Stack

- **Deep Learning**: PyTorch, CNNs, GAN architecture design
- **Mathematics**: Loss engineering, Wasserstein distance, gradient penalty
- **Engineering**: argparse CLI interface, reproducibility setup, shell scripting
- **Experiment Tracking**: TensorBoard logging, image checkpoints
- **Data Processing**: OpenCV, custom dataset parsing

