# Pytorch_DOLG
PyTorch implementation of "DOLG: Single-Stage Image Retrieval with Deep Orthogonal Fusion of Local and Global Features"

reference: https://arxiv.org/pdf/2108.02927.pdf

# Prerequisites
- PyTorch
- PyTorch Lightning
- timm
- sklearn
- pandas
- jpeg4py
- albumentations
- python3
- CUDA

# Data
You can get the GLDv2 dataset from [here](https://github.com/cvdfoundation/google-landmark).
If you just want the GLDv2-clean dataset, check this [kaggle competition dataset](https://www.kaggle.com/c/landmark-retrieval-2021).
Place your data like the structure below
```
data
├── train_clean.csv
└── train
    └── ###
        └── ###
            └── ###
                └── ###.jpg
```
