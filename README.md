# Medical Data Classification

A two-milestone machine learning project applying classical and deep learning
methods to medical datasets, with a focus on handling severe class imbalance.

**Authors:** Alessandro Annibale Cioffi, David Gorgiev, Sacha Heizmann  
**Course:** CS-233 - Introduction to Machine Learning, EPFL (Spring 2025)

## Overview

### Milestone 1: Classical ML on Heart Disease Data
Classification of heart disease severity (5 classes) from 13 clinical features
using the [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease).
Methods implemented from scratch: k-Nearest Neighbours, k-Means, and Logistic
Regression. Class imbalance was addressed through inverse frequency weighting.

### Milestone 2: Deep Learning on Skin Lesion Images
Classification of dermoscopic images across 7 diagnostic categories using the
[DermaMNIST](https://medmnist.com/) dataset (9,012 images, 28×28 RGB). Implemented
and compared MLP and CNN architectures in PyTorch, with cubic root class
weighting to handle extreme imbalance (103 to 6,034 samples per class).

## Results

| Method | Test Accuracy | Test F1 |
|---|---|---|
| kNN (k=9) | 60.0% | 0.339 |
| k-Means (k=48) | 60.0% | 0.318 |
| Logistic Regression | 65.0% | 0.464 |
| MLP (320 epochs) | 70.82% | 0.491 |
| CNN (4 layers, 150 epochs) | 74.11% | 0.580 |

## Note on Visibility
Public release of this repository was authorised by CS-233 staff (Spring 2025).
See `PublicRepo-Authorisation-Proof.PNG` at the root of the repo.
