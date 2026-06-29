# Spectral and Dynamical Analysis of Asteroid Families [☄️]

## Overview

This project extends a spectral asteroid taxonomy pipeline by integrating compositional and orbital information into a unified machine learning framework. The objective is to investigate asteroid family structure, predict taxonomy from orbital dynamics, evaluate family purity, and identify potential interlopers using supervised and unsupervised learning.

---

## Features

- Integration of SMASS-II spectral observations with AstDyS orbital data
- Spectral–orbital dataset construction through crossmatching
- Spectral and orbital feature engineering
- Belt composition mapping
- Asteroid family purity and entropy analysis
- Orbital-only taxonomy prediction
- Spectral–orbital taxonomy prediction
- Hidden structure discovery using UMAP and HDBSCAN
- Autoencoder-based representation learning
- Interloper detection through anomaly scoring

---

## Workflow

```
SMASS-II Spectra
        +
AstDyS Orbital Data
        │
        ▼
Crossmatching
        │
        ▼
Feature Engineering
        │
        ▼
Unified Dataset
        │
        ├── Belt Composition Mapping
        ├── Family Purity Analysis
        ├── Taxonomy Prediction
        ├── Hidden Structure Discovery
        └── Interloper Detection
```

---

## Dataset

### SMASS-II

- Visible reflectance spectra
- 1,339 labeled asteroid spectra

### AstDyS

- Proper orbital elements
- Family assignments
- More than one million asteroid records

### Unified Dataset

- 1,181 matched asteroids
- Spectral + orbital information

---

## Machine Learning

### Classification

- Random Forest
- XGBoost
- Multi-Layer Perceptron

### Representation Learning

- Autoencoder
- UMAP
- HDBSCAN

---

## Key Results

- Orbital-only taxonomy prediction demonstrated that orbital dynamics retain measurable compositional information.
- Combining spectral and orbital information substantially improved taxonomy prediction performance.
- Family purity analysis quantified compositional homogeneity across asteroid families.
- Autoencoder latent representations enabled hidden structure discovery.
- Composite anomaly scoring identified candidate interlopers within asteroid families.

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- XGBoost
- UMAP
- HDBSCAN
- Matplotlib
- Jupyter Notebook

---

## Research Contributions

- Unified spectral–orbital dataset construction
- Family purity assessment
- Orbital taxonomy prediction
- Spectral–orbital feature fusion
- Hidden structure discovery
- Interloper detection framework
