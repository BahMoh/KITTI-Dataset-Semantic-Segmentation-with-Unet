# KITTI-Dataset-Semantic-Segmentation-with-Unet

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

This repository contains a **PyTorch implementation of U-Net** for multi-class (29 class) semantic segmentation on the KITTI Semantic dataset.

## About
U-Net is a convolutional neural network architecture for image segmentation with an encoder-decoder structure and skip connections. This project implements U-Net for **multi-class semantic segmentation**, where each pixel is assigned one of 29 semantic classes.

## Dataset
The semantic segmentation dataset can be downloaded using:

```bash
wget https://s3.eu-central-1.amazonaws.com/avg-kitti/data_semantics.zip
unzip data_semantics.zip
```
### Dataset Structure
```bash
training/
├── image_2/
│   ├── 000001.png
│   └── ...
└── semantic_rgb/
    ├── 000001.png
    └── ...
```

## Setup
Install required packages:
```bash
pip install torch torchvision numpy opencv-python pillow tqdm scikit-learn matplotlib
```
