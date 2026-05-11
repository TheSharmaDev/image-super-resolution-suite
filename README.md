# Multi-Model Super Resolution

This project focuses on image super resolution using different deep learning models. The goal is to convert low-resolution images of size 24×24 into high-resolution images of size 128×128 while preserving image quality and details.

The repository contains implementations and comparisons of multiple super resolution techniques, including GAN-based and hybrid approaches.

---

# Project Objective

Image super resolution is a computer vision task that enhances the quality and resolution of low-resolution images.

In this project:
- Input image resolution: 24×24
- Output image resolution: 128×128

Different deep learning models are used to reconstruct sharper and more detailed high-resolution images from low-resolution inputs.

---

# Models Implemented

## 1. SRGAN
SRGAN (Super Resolution Generative Adversarial Network) uses a generator and discriminator network to generate realistic high-resolution images.

Features:
- GAN-based architecture
- Produces visually sharper images
- Improves texture details

---

## 2. Real-ESRGAN
Real-ESRGAN is an advanced super resolution model designed for real-world image enhancement.

Features:
- Better reconstruction quality
- Handles noisy and blurred images
- Generates realistic high-resolution outputs

---

## 3. Hybrid Super Resolution Model
This model combines multiple deep learning techniques for image enhancement and resolution improvement.

Features:
- Hybrid architecture
- Improved reconstruction performance
- Better feature extraction

---

# Repository Structure

```bash
multi-model-super-resolution/
│
├── genaiproject.ipynb
├── hybrid-model.ipynb
├── SRGAN & REAL-ESRGAN.ipynb
├── README.md
└── requirements.txt
```

---

# Files Description

## `genaiproject.ipynb`
Main notebook containing the complete workflow for image super resolution.

## `hybrid-model.ipynb`
Implementation of the hybrid super resolution model.

## `SRGAN & REAL-ESRGAN.ipynb`
Implementation and comparison of:
- SRGAN
- Real-ESRGAN

---

# Technologies Used

- Python
- TensorFlow / PyTorch
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

---

# Applications

Image super resolution has many real-world applications:

- Medical imaging
- Satellite image enhancement
- CCTV footage enhancement
- Image restoration
- Video quality improvement
- AI photography

---

# How to Run the Project

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/multi-model-super-resolution.git
```

## 2. Move to the Project Directory

```bash
cd multi-model-super-resolution
```

## 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

## 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

## 5. Run the Notebooks

Open and run:
- `genaiproject.ipynb`
- `hybrid-model.ipynb`
- `SRGAN & REAL-ESRGAN.ipynb`

---

# Results

The implemented models successfully enhance low-resolution images from 24×24 to 128×128 resolution.

The project compares different models based on:
- Image sharpness
- Texture quality
- Visual appearance
- Reconstruction performance

---

# Future Improvements

- Add more advanced super resolution architectures
- Improve evaluation metrics such as PSNR and SSIM
- Train on larger datasets
- Deploy as a web application
- Optimize for real-time inference

---

# Conclusion

This project demonstrates how different deep learning models can be used for image super resolution and image enhancement. The comparison between SRGAN, Real-ESRGAN, and hybrid models helps analyze the strengths of different approaches for generating high-quality images from low-resolution inputs.

---

# Author

Rohit Sharma
