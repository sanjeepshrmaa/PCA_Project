# PCA for Dimensionality Reduction and Image Reconstruction

This project explores the use of **Principal Component Analysis (PCA)** for compressing and reconstructing images. PCA is a widely used dimensionality reduction technique that projects data into a lower-dimensional space while preserving as much variance as possible. Here, it is applied to image datasets to show how dimensionality reduction affects reconstruction quality.

## Project Overview

- **Dimensionality Reduction:** Images are represented in a lower-dimensional space using PCA.  
- **Image Reconstruction:** Compressed images are projected back to the original space to visualize reconstruction quality.  
- **Evaluation:** Reconstruction loss is measured, and side-by-side comparisons of original vs reconstructed images are provided. 

## How It Works
1. Images are resized and flattened into vectors.
2. PCA is applied to transform these high-dimensional vectors into a smaller feature space.
3. The compressed representation is then inverted to reconstruct the images.
4. Side-by-side comparisons illustrate the trade-off between compression and quality.


This project is simple, interpretable, and educational, making it a great introduction to applying PCA in computer vision.


