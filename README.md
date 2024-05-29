# StackGAN Image Generation

## Overview

This project implements Stage-I of StackGAN, a Generative Adversarial Network (GAN) that generates low-resolution images from textual descriptions. StackGAN employs a novel approach where Stage-I generates a coarse image. The project focuses on understanding the impact of different embedding models and datasets on the performance of StackGAN. The project includes three trials, each represented by a folder containing result pictures, model parameters, a Kaggle notebook, and final embeddings.

## Features

- **Stage-I GAN**: Generates coarse, low-resolution images.
- **Conditioning Augmentation**: Introduces variability and prevents mode collapse.
- **Adversarial and Conditioning Augmentation Loss**: Ensures realistic and text-consistent images.

## Experiments

### Trial 1: Baseline Implementation

- **Folder**: `Birds_dataset_embedding`
- **Dataset**: CUB 200 2011
- **Embedding Model**: Original model from StackGAN paper
- **Contents**: 
  - Result pictures
  - Model parameters (`.pth` files)
  - Kaggle notebook for the code
  - Final embeddings (if needed)

### Trial 2: Alternative Embedding Model and Dataset

- **Folder**: `Flicker30k`
- **Dataset**: Flicker30k
- **Embedding Model**: BERT
- **Contents**: 
  - Result pictures
  - Model parameters (`.pth` files)
  - Kaggle notebook for the code
  - Final embeddings (if needed)

### Trial 3: Original Dataset with Alternative Embedding Model

- **Folder**: `birds_dataset_bert_generated_emb`
- **Dataset**: CUB 200 2011
- **Embedding Model**: BERT
- **Contents**: 
  - Result pictures
  - Model parameters (`.pth` files)
  - Kaggle notebook for the code
  - Final embeddings (if needed)

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow or PyTorch


### Results

- Results from each trial can be found in the respective folders: `Birds_dataset_embedding`, `Flicker30k`, and `birds_dataset_bert_generated_emb`.
- Visual examples of generated images are provided in the result folders.
