# Financial Health Scoring using BGMM

## Overview
This project demonstrates how to build a financial health score using Bayesian Gaussian Mixture Models.

## Why this matters
Traditional credit scores fail to capture holistic financial behaviour.

## Approach
- Behavioural feature design (Save, Plan, Spend, Borrow)
- Bayesian Gaussian Mixture Model
- Soft clustering
- Entropy-based feature weighting
- Continuous score generation

## Results
- Smooth financial health score (1–100)
- Interpretable behavioural gradients

## Key Features
- Fully unsupervised
- Explainable (SHAP-style contributions)
- Reproducible with synthetic data

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
