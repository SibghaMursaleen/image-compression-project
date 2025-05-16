# Image Compression for Efficient Storage and Transmission

This project implements and compares two image compression techniques — JPEG (DCT-based) and JPEG2000-like (using Haar Wavelet Transform) — to explore efficient methods for image storage and transmission. The implementation supports both grayscale and RGB images, providing both visual outputs and quantitative evaluation using Compression Ratio, PSNR, and SSIM.

---

## 📌 Features

- ✅ JPEG Compression using Discrete Cosine Transform (DCT)
- ✅ JPEG2000-like Compression using Haar Wavelet Transform
- ✅ Supports both grayscale and RGB images
- ✅ Compression Ratio, PSNR, and SSIM evaluation
- ✅ Visual comparison of original and compressed images
- ✅ Clean and modular code in Python (Google Colab-ready)

---

## 🧠 Algorithms Used

### 1. JPEG Compression (DCT-Based)
- Convert image to YCbCr (for RGB)
- Block-wise DCT transformation
- Quantization and zigzag scanning
- Entropy encoding (basic)

### 2. JPEG2000-like Compression (Haar Transform)
- Multi-level Haar Wavelet Decomposition
- Thresholding for compression
- Inverse Haar for reconstruction
