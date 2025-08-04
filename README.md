# IP-NFDE

**Implicit Prior–Nonlinear Fractional Diffusion Equation and Their Application in Image Processing**

This repository contains the implementation of a hybrid image denoising model that combines **Implicit Prior** and **Nonlinear Fractional Diffusion Equation (NFDE)** to effectively remove noise — especially **gamma-distributed speckle noise** — from images. The model is particularly suitable for medical imaging (e.g., ultrasound) and remote sensing applications.

## 🔬 Key Features

- Combines PDE-based and deep prior-based techniques
- Supports Deep Image Prior (DIP) and SwinIR priors
- Handles gamma-distributed speckle noise efficiently
- Plug-and-play denoising with visual results

---

## 🚀 User Test (Google Colab)

You can try out the model directly using the following Colab notebooks:

### 🖼️ Denoise a Pre-noised Image

Click below to open a Colab notebook where you can upload your **noisy image**, and the model will perform denoising:

[![Open In Colab - Noisy Image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mdkarimullahaque/IP-NFDE/blob/main/IP_NFDE_Noisy_Image.ipynb)

---

### 📷 Denoise a Clean Image After Adding Custom Noise

Click below to upload a **clean image**, choose the noise level (L), and see how the model performs denoising on artificially noised input:

[![Open In Colab - User Image + Noise](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mdkarimullahaque/IP-NFDE/blob/main/IP_NFDE_User_Image.ipynb)

---

## 📊 Evaluation Metrics

- **PSNR (Peak Signal-to-Noise Ratio)**
- **SSIM (Structural Similarity Index)**

These metrics are automatically computed after denoising and displayed at the end of the notebook.

