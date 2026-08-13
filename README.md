# DDPM-Handwritten-Digit-Image-Generation
Lightweight Denoising Diffusion Probabilistic Model for MNIST Handwritten Digit Generation
Support Kaggle Notebook & Local PC training, auto GPU/CPU device adapt.

## Project Feature
1. Sinusoidal timestep embedding + Lightweight UNet backbone
2. Standard DDPM forward diffusion & reverse sampling
3. Compatible Kaggle oddrationale/mnist-in-csv dataset
4. Auto plot loss convergence curve & 4x4 generated sample grid
5. Complete error check: file exist verify, device auto detect

## Quick Start
### 1. Install Dependencies
```bash
pip install -r requirements.txt
