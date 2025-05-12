# 🛰️ Simplified SatMAE: Masked Autoencoder for Satellite Imagery

This project implements a **simplified version of SatMAE**, a Masked Autoencoder architecture applied to satellite images. It explores the self-supervised learning technique of reconstructing masked image patches, ideal for Earth observation and geospatial intelligence research.

---

## 🔍 Overview

Masked Autoencoders (MAEs) are powerful models for learning efficient visual representations by masking portions of the input and training the model to reconstruct them. This project adapts the MAE idea to satellite images (e.g., Sentinel-2), offering a foundation for:

- Pretraining satellite imagery encoders
- Feature extraction for downstream tasks (e.g., land use, deforestation, etc.)
- Educational purposes in geospatial ML

---

## 🛠️ Key Components

- ✅ Simple encoder-decoder transformer architecture
- ✅ Random patch masking of input satellite images
- ✅ Reconstruction loss (MSE)
- ✅ Visualization of input, masked, and reconstructed images

---

## 🧰 Tech Stack

- Python
- PyTorch
- NumPy
- Matplotlib (for image visualization)

---

## 📁 Directory Structure


