# KITTI-Dataset-Semantic-Segmentation-with-Unet

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

This repository contains a **PyTorch implementation of U-Net** for multi-class semantic segmentation on the KITTI Semantic dataset.

## Table of Contents
- [About](#about)
- [Dataset](#dataset)
- [Setup](#setup)
- [Data Preprocessing](#data-preprocessing)
- [Model Architecture](#model-architecture)
- [Loss Function](#loss-function)
- [Training & Validation](#training--validation)
- [Evaluation](#evaluation)
- [Visualization](#visualization)
- [Usage](#usage)
- [License](#license)
- [References](#references)

## About
U-Net is a convolutional neural network architecture for image segmentation with an encoder-decoder structure and skip connections. This project implements U-Net for **multi-class semantic segmentation**, where each pixel is assigned one of 29 semantic classes.

## Dataset
The semantic segmentation dataset can be downloaded using:

```bash
wget https://s3.eu-central-1.amazonaws.com/avg-kitti/data_semantics.zip
unzip data_semantics.zip
```
