"""# SimAccel Capital Optimisation Demo

This notebook demonstrates how surrogate models can be used to accelerate internal capital model evaluations in insurance, with a focus on Solvency II-style capital optimisation problems.

## 📌 Overview

**Objective:** 
Estimate Solvency Capital Requirements (SCR) across various reinsurance configurations (retention and quota share) using a Gaussian Process surrogate, replacing a slow-running internal capital model.

## 📁 Files

- `SimAccel_CapitalOptimisationDemo.ipynb`: Jupyter notebook with full demo
- `README.md`: This documentation file

## ⚙️ Contents of the Notebook

1. **Scenario Generation** – Create synthetic data mimicking capital model outputs
2. **Surrogate Model Training** – Train a Gaussian Process model on real samples
3. **Prediction Grid** – Predict SCR over a dense grid of reinsurance options
4. **Visualisation** – Contour plot of predicted SCR to identify optimal regions

## 📦 Technologies Used

- Python 3
- `numpy`, `scikit-learn`, `matplotlib`
- Gaussian Process Regression (GPR)
- Synthetic simulation for internal model logic

## 📈 Output Example

The notebook generates a contour plot showing SCR predictions across a range of retention levels and quota share parameters. This allows actuaries or risk managers to quickly identify capital-efficient reinsurance structures.

## 🔄 Next Steps

- Add Uncertainty Quantification using GP variance
- Introduce model explainability (e.g., SHAP, gradients)
- Re-run selected scenarios using full ICM for validation

## 🧠 Author

Kgosi
April 2025
"""
