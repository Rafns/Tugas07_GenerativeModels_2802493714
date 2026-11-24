# Deep Learning Assignment: Generative Models & Classifier Study

This repository provides a complete PyTorch implementation and empirical evaluation framework for comparative analysis of deep generative models and baseline classifiers on the Fashion-MNIST dataset.

## Project Scope
The study investigates seven distinct neural network architectures to understand representation learning, reconstruction capabilities, generative synthesis, and information bottlenecks:
- **Baseline Classifier**: Multi-Layer Perceptron (MLP) analyzing information bottleneck properties.
- **Autoencoders**: Vanilla Autoencoder (AE) and Sparse Autoencoder (L1 penalty).
- **Probabilistic Generative Models**: Variational Autoencoder (VAE) and Denoising Diffusion Probabilistic Models (DDPM with Light U-Net).
- **Adversarial Models**: Vanilla GAN and Deep Convolutional GAN (DCGAN).

## Evaluation Framework
- **Fidelity Metrics**: Mean Squared Error (MSE), Peak Signal-to-Noise Ratio (PSNR), and Structural Similarity Index (SSIM).
- **Generative Performance**: Fréchet Inception Distance (FID).
- **Computational Efficiency**: Epoch training duration and batch inference latency.

## Getting Started

### Prerequisites
- Python 3.8 or higher
- PyTorch and TorchVision (GPU execution with CUDA recommended)

### Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/Rafns/Tugas07_GenerativeModels_2802493714.git
cd Tugas07_GenerativeModels_2802493714
pip install -r requirements.txt
```

### Execution
Open and run `TUGAS_DL_SESI07.ipynb` sequentially using Jupyter Notebook or Google Colab.

## Repository Contents
- `TUGAS_DL_SESI07.ipynb`: Core experimental code, training loops, and visualizations.
- `TUGAS_DL_SESI07_2802493714_Rafael_Nandana_S.pdf`: Detailed analytical report.
- `requirements.txt`: Python package requirements.
- `README.md`: Documentation.
