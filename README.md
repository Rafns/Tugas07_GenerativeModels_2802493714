# Empirical Comparative Study of Generative Models & MLP Classifier Evaluation

This repository contains the PyTorch implementation for the Deep Learning Take-Home Assignment Session 07. The project focuses on a full-scale empirical comparative study of generative model architectures and classification evaluation using the Fashion-MNIST dataset.

## Implemented Models
- MLP Classifier (Baseline & Information Bottleneck Analysis)
- Vanilla Autoencoder (AE)
- Sparse Autoencoder with L1 Sparsity Penalty
- Variational Autoencoder (VAE)
- Vanilla Generative Adversarial Network (GAN)
- Deep Convolutional GAN (DCGAN)
- Denoising Diffusion Probabilistic Models (DDPM - Light U-Net)

## Evaluation Metrics
- **Reconstruction Fidelity**: Mean Squared Error (MSE), Peak Signal-to-Noise Ratio (PSNR), Structural Similarity Index (SSIM).
- **Generative Quality**: Fréchet Inception Distance (FID) Score.
- **Performance/Efficiency**: Training time per epoch, Inference Latency per batch.

## Prerequisites
Ensure you have Python 3.8+ installed. A GPU is highly recommended (e.g., NVIDIA T4 on Google Colab) to accelerate the training and inference processes.

## Installation and Execution
Clone this repository:
```bash
git clone https://github.com/Rafns/Tugas07_GenerativeModels_2802493714.git
cd Tugas07_GenerativeModels_2802493714
```

Install the required dependencies:
```bash
pip install -r requirements.txt
```

Running the Experiment:
1. Open the `TUGAS_DL_SESI07.ipynb` file using Jupyter Notebook, Jupyter Lab, or Google Colab.
2. Run all cells sequentially.

## Highlights
- **Generative Trilemma Verified**: Empirical results demonstrate trade-offs between sampling speed, sample quality, and mode coverage across models like VAE, DCGAN, and DDPM.
- **Information Bottleneck**: Empirical analysis showing how classification models compress input space and discard features necessary for reconstruction or generation.

## Repository Structure
- `TUGAS_DL_SESI07.ipynb`: The main experiment script (Data Loading, Training, Evaluation, Visualizations).
- `TUGAS_DL_SESI07_2802493714_Rafael_Nandana_S.pdf`: The comprehensive final analysis report.
- `requirements.txt`: List of required Python libraries.
- `README.md`: Project documentation.
