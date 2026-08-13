# DDPM-Handwritten-Digit-Image-Generation
Lightweight Denoising Diffusion Probabilistic Model for MNIST Handwritten Digit Generation
Support Kaggle Notebook & Local PC training, auto GPU/CPU device adapt.

## Project Feature
1. Sinusoidal timestep embedding + Lightweight UNet backbone
2. Standard DDPM forward diffusion & reverse sampling
3. Compatible Kaggle oddrationale/mnist-in-csv dataset
4. Auto plot loss convergence curve & 4x4 generated sample grid
5. Complete error check: file exist verify, device auto detect

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Dataset Prepare
#### Local Environment
Download mnist_train.csv from Kaggle: https://www.kaggle.com/oddrationale/mnist-in-csv
Put csv file path in train.py csv_path variable.

#### Kaggle Notebook
Add dataset oddrationale/mnist-in-csv, default path is ready to use.

### 3. Run Train
```bash
python train.py
```

#### Output Result
outputs/loss_convergence.png: Training loss curve
outputs/synthesized_samples.png: 16 generated MNIST digits grid

## Quick Start



