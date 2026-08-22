# XAI-Stability-Bench

## Overview

XAI-Stability-Bench is a research project focused on evaluating the
stability of Explainable Artificial Intelligence (XAI) methods under
different perturbations of machine learning models and datasets.

The project investigates explanation stability using SHAP and LIME
across multiple classification datasets and machine learning models.

## Objectives

The main objectives of the project are:

- Generate model explanations using SHAP and LIME.
- Evaluate the stability of explanations under different perturbations.
- Compare explanation stability across different machine learning models.
- Compare stability across different datasets.
- Develop a systematic framework for evaluating XAI explanation stability.

## Datasets

Four classification datasets are used:

- Titanic
- Breast Cancer Wisconsin Diagnostic
- Adult Income
- Bank Marketing

## Machine Learning Models

Each dataset is used to train four classification models:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

## Model Evaluation

Baseline model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

Confusion matrices and classification reports are also generated.

## Explainability Methods

The project uses:

- SHAP
- LIME

## Stability Analysis

Explanation stability is evaluated under different perturbations,
including:

- Random seed changes
- Gaussian noise
- Removal of 5% training data
- Train-test split changes
- Hyperparameter changes

The following stability metrics are considered:

- Spearman Rank Correlation
- Kendall Tau
- Jaccard Similarity
- Cosine Similarity

## Repository Structure

```text
XAI-Stability-Bench/
│
├── datasets/
├── notebooks/
│   ├── model_training/
│   └── xai/
├── models/
├── results/
├── explanations/
├── stability_results/
└── figures/
