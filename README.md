# GAN-Enhanced Gastrointestinal Disease Classification

This project explores the use of Generative Adversarial Networks (GANs) to improve gastrointestinal (GI) disease classification from endoscopic images, particularly using the Kvasir v2 dataset.

## 🧠 Project Overview

This repository contains partial work on a deep learning pipeline for GI image classification, aiming to:

- Enhance data diversity using GAN-generated synthetic samples.
- Improve classification accuracy on underrepresented disease classes.
- Apply preprocessing techniques to improve lesion visibility.
- Optionally visualize model decision-making using explainability tools.

## 🧰 Components Implemented So Far

- ✅ Preprocessing with CLAHE and Gaussian Smoothing
- ✅ ConvMixer-based classifier with External Attention
- ✅ Initial setup for training and evaluation
- 🔄 (In progress) GAN-based data augmentation with StyleGAN2-ADA
- 🔄 (Planned) Grad-CAM-based post-processing visualization


📊 Dataset

Kvasir v2
 — Contains 8 GI classes such as polyp, esophagitis, ulcerative colitis, etc.
 



