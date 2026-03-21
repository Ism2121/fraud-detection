# Credit Card Fraud Detection

## Overview
A fraud detection system built in Python using the Kaggle Credit Card Fraud Detection dataset (MLG-ULB). This project progresses from rule-based detection through machine learning models.

## Dataset
- 284,807 transactions
- 492 confirmed fraud cases (0.17% of dataset)
- Features V1-V28 are PCA-transformed for privacy
- Source: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Project Structure
- `notebooks/` — Jupyter notebooks numbered in order
- `src/` — reusable Python modules
- `data/` — dataset (not tracked, download from Kaggle)

## Phase 1: Rule-Based Detection
Built threshold-based detection rules using V14, V17, and V3.
- Best rule: (V14 < -6 AND V17 < -4) OR (V3 < -5 AND V14 < -6)
- Catch rate: 54.07%
- False positives: 46

## Phase 2: Machine Learning (in progress)